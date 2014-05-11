
#include <iostream>
using namespace std;

int max(int*, int*);
int main ()
{
int num1;
int num2;
cout<< "Enter the first number"<<endl;
cin>>num1;

cout<<"Enter the second number"<<endl;
cin>>num2;

cout<< "The maximum number between"<<num1<<num2<< "is"<<max(num1, num2);

system ("pause");
return 0;

int max(int n1, int n2)
{
int res;
if (n1>n2)

res=*n1;

else

res=*n2;

return res;
}
