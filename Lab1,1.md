#include <iostream>
#include <math.h>
#include <stdio.h>

/* run this program using the console pauser or add your own getch, system("pause") or input loop */
using namespace std;
int main(int argc, char** argv) 
{double r,k,g,m;

cout<<"R=";cin>>r;
cout<<"K=";cin>>k;
g=sin(r+3*k*k)-sqrt(r+4*k);
m=pow((k-12*((r-4)/(1+3*k))),2)+k;
printf("G=%lf\nM=%lf\n",g,m);

	return 0;
}
		
