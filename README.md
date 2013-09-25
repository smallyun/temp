temp
====

translate temperature
#include<iostream>
using namespace std;
int trans(int f)
{
   int c;
   c=5/9*(f-32);
   return c;
}
void main()
{
  int f;
  cin>>f;
  cout<<trans(f)<<endl;
}
