# Add-two-numbers
#include <iostream>
using namespace std;

int addition(int a,int b);

int main()
{
	int a,b;
	int add;	
	

	cout<<"Enter first number: ";
	cin>>a;
	cout<<"Enter second number: ";
	cin>>b;
	

	add=addition(a,b);
	

	cout<<"Addition is: "<<add<<endl;
	
	return 0;
}


int addition(int a,int b)
{
	return (a+b);
	
}
