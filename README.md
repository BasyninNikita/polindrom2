#include <iostream>
#include <cstring>
using namespace std;
short code(char a)
{
    short b;
    b = (short)a;
    return b;
    }

int main()
{
string str;string str1;
cout<<"enter the word:";
cin>>str;
int dl= str.length();
int j=0;
for(int i=0;i!=dl;i++)
{
   if (code(str[i])>64) {
		    if (code(str[i])<91) {str1+=str[i];}
		}
		if (code(s[i])>96) {
		    if (code(str[i])<123) {str1+=str[i] - 32;}
		}
		if (code(str[i])>47) {
		    if (code(str[i])<58) {str1+=str[i];}
		}
dl=str1.length();
for(int i=0;i!=dl/2;i++)
{
    if(str[i]!=str1[dl-i-1])
    {
      cout<<"0";j=1;break;
    }
}
if(j==0)
{
   cout<<"1";
}
    return 0;
}
