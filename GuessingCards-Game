#include <stdio.h>
#include <stdlib.h>
#include <windows.h>
#include <time.h>

int main(){
	int a, b, pary = 4,x,y,m,n;
	char k1 = '1', k2 = '2', k3 = '3', k4 = '4', k5 = '5', k6 = '6', k7 = '7', k8 = '8';
	char h1='#',h2='#', a1='&',a2='&', z1='@', z2 = '@', p1 = '%', p2='%';

	while (pary >= 0) {
	//Sleep(1000);
	system("cls");
	printf("***   ***   ***   ***\n");
	printf("*%c*   *%c*   *%c*   *%c*\n", k1, k2, k3, k4);
	printf("***   ***   ***   ***\n\n");

	printf("***   ***   ***   ***\n");
	printf("*%c*   *%c*   *%c*   *%c*\n", k5, k6, k7, k8);
	printf("***   ***   ***   ***\n");

do{
	printf("Zadej 1. kartu: ");
	scanf("%i",&a);
	m++;

}	while(a>9 && a<0);
	switch (a){
		case 1: printf("Pod kartou je %c\n",h1); break;
		case 2: printf("Pod kartou je %c\n",a1); break;
		case 3: printf("Pod kartou je %c\n",z1); break;
		case 4: printf("Pod kartou je %c\n",p1); break;
		case 5: printf("Pod kartou je %c\n",h2); break;
		case 6: printf("Pod kartou je %c\n",a2); break;
		case 7: printf("Pod kartou je %c\n",z2); break;
		case 8: printf("Pod kartou je %c\n",p2); break;
	}
	do{
		printf("Zadej 2. kartu: ");
		scanf("%i",&b);
		n++;
		
	} while(a>9 && a<0);
	switch (b){
		case 1: printf("Pod kartou je %c\n",h1); break;
		case 2: printf("Pod kartou je %c\n",a1); break;
		case 3: printf("Pod kartou je %c\n",z1); break;
		case 4: printf("Pod kartou je %c\n",p1); break;
		case 5: printf("Pod kartou je %c\n",h2); break;
		case 6: printf("Pod kartou je %c\n",a2); break;
		case 7: printf("Pod kartou je %c\n",z2); break;
		case 8: printf("Pod kartou je %c\n",p2); break;
	}
	if(a == 1 && b == 5){
		k1 = ' ';
		k5 = ' ';
		pary--;
		
		}
	else if(b==1 && a==5){
		k1 = ' ';
		k5 = ' ';
		pary--;
	}
	
	if(a==2 && b==6){
		k2 = ' ';
		k6 = ' ';
		pary--;
		
		}
	else if(a==6 && b==2){
		k2 = ' ';
		k6 = ' ';
		pary--;
	}
	
	if(a==3 && b==7){
		k3 = ' ';
		k7 = ' ';
		pary--; 
	}
	else if(a==7 && b==3){
		k3 = ' ';
		k7 = ' ';
		pary--; 
	}
	if(a==4 && b==8){
		k4 = ' ';
		k8 = ' ';
		pary--;
	}
	else if(a==8 && b==4){
		k4 = ' ';
		k8 = ' ';
		pary--;
	}
	getchar(); getchar();
	if(pary==0) break;
	}
	system("cls");
	system("mode 50,20");
	do{
		printf("\n");
		x++;
	} while(x<10);
	
	do{
		printf(" ");
		y++;
	} while(y<20);
	printf("Vyhral jsi");
	printf("\n                 Pocet pokusu: %i",m);
	getchar();
}
