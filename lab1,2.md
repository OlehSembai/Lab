#include <iostream>
#include <math.h>
#include <stdio.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */
using namespace std;
int main(int argc, char** argv) 
{double a,b,x,y;
cout<<"a=";cin>>a;
cout<<"b=";cin>>b;
cout<<"x=";cin>>x;
y=asin(x)*pow(tan(a*x),2)- log(2*x)+(exp(b*x)/pow(x,1.0/3.0));

cout<<"y="<<y<<endl;

	return 0;
}
		
