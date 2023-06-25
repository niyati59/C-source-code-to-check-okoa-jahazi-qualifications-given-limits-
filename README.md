#include <stdio.h>
int main(){
 float balance;
 
 
 printf("Enter your balance(in KES):");
 scanf("%f",&balance);
 
 
 if(balance>=20.0){
	 printf("CONGRATULATIONS!! You are eligible for Okoa Jahazi.\n");

 }
	else{
		printf("Sorry , you are not eligible for Okoa Jahazi.\n");
	}
	
	
	return 0;
}
