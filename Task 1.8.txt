#include<iostream.h>
#include<stdio.h>
#include<string.h>
void main()
{
 int n,x=0;
 char s[];
 cout<<"\nNumber of statements: ";
 cin>>n;
 cout<<"\nEnter the statements: ";
 for(int i=0;i<n;i++)
 {
  gets(s);
  int j=0;
  while(j<strlen(s))
  {
   if(s[j]=='+')
      x++;
    else
      x--;
    j++
   }
  }
 }