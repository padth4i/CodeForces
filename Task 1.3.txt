#include<iostream.h>
#include<conio.h>
#include<string.h>

void main()
{
 int n,l;
 char s[];
 cout<<"Enter number of words to abbreviate: ";
 cin>>n;
 cout<<"\nEnter the words to abbreviate: ";
 for(int i=0;i<n;i++)
 {
  gets(s);
  l=strlen(s);
  if(l>10)
   cout<<s[0]<<l-2<<s[l-1];
  else
   cout<<s;
  }