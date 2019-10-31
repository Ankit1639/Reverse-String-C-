# Reverse-String-C-
Program to reverse string using C++ programming language
Reversing a string using some string functions and some of the libraries.
#include<fstream.h>
#include<conio.h>
#include<studio.h>
#include<string.h>
void main()
{
clrscr();
Char x;
ifstream ifile;
ofstream o1;
ifile.open("base.txt",ios::in);
o1.open("copy.txt",ios::out);
while(!ifile.eof())
{
 char ch[80];
 int n=0;
 ifile.get(x);
 while((x!='')&(!ifile.eof())
 {
 str[n]=x;
 n++;
 ifile.get(x);
 }
 str[n]='\0';
 cout<<strrev(str);
 cout<<"";
 }
 ifile.close();
 o1.close();
 getch();
 }
