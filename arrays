#include <stdio.h>
#include <stdlib.h>

//dizi elemanlarını büyükten küçüğe sıralayan program
int main(int argc, char *argv[]) {
	int A[5];
	int i,j;
	int temp;
	for(i=0;i<5;++i){
		printf("dizi elemanini girin:");
		scanf("%d",&A[i]);
		
	}
	for (i=0;i<5;i++){
		for(j=i+1;j<5;j++){
			if(A[j]>A[i]){
				temp=A[j];
				A[j]=A[i];
				A[i]=temp;
			}
		}
	}
		for(i=0;i<5;++i){
			printf("%d\n",A[i]);
			
		}
	return 0;
}


//kücükten büyüğe sıralama
int main(int argc, char *argv[]) {
	int a[5];
	int i,j;
	int temp;
	for(i=0;i<5;i++){
		printf("elemanlari girin");
		scanf("%d",&a[i]);
	}
	for(i=0;i<5;i++){
		for(j=i+1;j<5;j++){
			if(a[j]<a[i]){
				temp=a[j];
				a[j]=a[i];
				a[i]=temp;
			}
		}
	}
	printf("Siralandi:\n");
	for(i=0;i<5;i++){
		printf("%d\n",a[i]);
	}
	
	return 0;
}


//dizinin en kücük elemanını bulan program
int main(int argc, char *argv[]) {
	int d1[5];
	int i;
	for(i=0;i<5;i++){
		printf("elemani giriniz:");
		scanf("%d",&d1[i]);
	}
	int enk;
	enk=d1[0];
	for(i=0;i<5;i++){
		if(d1[i]<enk){
			enk=d1[i];
			printf("dizinin en kucuk elemani: %d",enk);
		}
			}	
	return 0;
}


/*dizi elemanlarını carpan program
int carp(int matris[],int size){
	int carpim=1;
	int i=0;
	for(;i<size;i++){
		
		carpim*=matris[i];
	}
	return carpim;
}


int main(int argc, char *argv[]) {
	int sayilar[5]={1,2,3,4,5};
	printf("%d",carp(sayilar,5));
	return 0;
}
*/



//matris olusturan program
int main(int argc, char *argv[]) {
	
int satir,sutun,i,j;
printf("satir sayisini girin:");
scanf("%d",&satir);
printf("sutun sayisini girin:");
scanf("%d",&sutun);

int matris [satir][sutun];
for(i=0;i<satir;i++){
	for(j=0;j<sutun;j++){
		printf("[%d][%d]=",i+1,j+1);
		scanf("%d",&matris[i][j]);
	}
}

printf("\n\n olusan matris:\n");
int k,n;
for (k=0;k<satir;k++){
	for(n=0;n<sutun;n++){
		printf("%d ",matris[k][n]);
	}
	printf("\n");
}
	return 0;
}
