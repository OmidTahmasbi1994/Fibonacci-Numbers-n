# Fibonacci-Numbers-n


#include <iostream>
#include <conio.h>

using namespace std;
int main()

{
	long i;
	cout<<"Enter a Positive Number:"<<endl;
	cin>>i;
	cout<<"Fibonacci Numbers < "<<i<<" : \n 0 , 1";
	
	long f0=0;
	long f1=1;
	
	while(true)
	{
		long f2 = f0 + f1 ;
		
		if(f2>i) 
		break;
		
		cout<<" , "<<f2;
		
		f0=f1;
		f1=f2;
		
		
	}
}
