#include<stdio.h>
#define PI 3.14

int main(){
	
int yaricap;
float hacim;

printf("kurenin yarıçapını giriniz");
scanf("%d",&yaricap);

hacim=4/3.0*PI*(yaricap*yaricap*yaricap);
printf("kurenin hacmi '%.2f' dir ",hacim);
	
	
	return 0;
}
