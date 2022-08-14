#include <stdio.h>
#include <stdlib.h>
#include <time.h>

/*factorial with function
int faktoriyel(int sayi){
	int fact=1;
	for(;sayi>0;sayi--){
		fact*=sayi;
	}
	return fact;
}

int main(int argc, char *argv[]) {
	int n,a;
	printf("faktoriyelini istediginiz sayiyi giriniz:");
	scanf("%d",&n);
	a= faktoriyel(n);
	printf("faktoriyel= %d",a);
	return 0;
}
*/


//sayisal loto yapma fonksiyonu;
/*
int sayisal_loto(){
	srand(time(NULL));
	int i,j;
	for(i=1;i<7;i++){
		printf("%d. kolon:",i);
		for(j=1;j<7;j++){
		printf("%d   ",1+rand()%45);
		
		}
		printf("\n");
	}
	}
int main(){
	sayisal_loto();
	return 0;
}
*/


//harf notu hesaplayan fonksiyon
/*
	void harf_notu(int vize,int final){
		double ort;
		ort=final*0.6+vize*0.4;
		if(ort>80 && ort<100){
			printf("aa");
			}
		else if(ort>70 && ort<80){
			printf("bb");
		}
		else if(ort>60 && ort<70){
			printf("cc");
		}
		else if(ort>50 && ort<60){
			printf("dd");
		}
		else if(ort<50){
			printf("ff");
		
	}
}
	
	int main(int argc, char *argv[]) {
	int vize,final;
	printf("VIZE NOTUNUZU GIRIN:");
	scanf("%d",&vize);
	printf("FINAL NOTUNUZU GIRIN:");
	scanf("%d",	&final);
	
	printf("HARF NOTUNUZ: ");
	harf_notu(vize, final);
	
	return 0;
}
*/



/*1den ne kadar olan sayilarin toplamını veren program*/
	int ntopla(int n){
		int i;
		int toplam=0;
		for(i=1;i<=n;i++){
			toplam+=i;
		}
		return toplam;
	}
	int main(int argc, char *argv[]) {
		int n;
		printf("Sayiyi girin:");
		scanf("%d",&n);
		ntopla(n);
		printf("sayilarin toplami= %d",ntopla(n));
	return 0;
}



// zar atma programi
void zar(){
	srand(time(NULL));
	int sayi=1+rand()%6;
	printf("%d",sayi);	
}
int main(int argc, char *argv[]) {
	zar();
	
	
	return(0);
}



// sayının asal mı armstrong mu mükemmel mi oldugunu bulan program
int asalmi(int sayi){
	int i;
	for(i=2;i<sayi;i++){
		if(sayi%i==0){
			return 0;
		}
		else{
			return 1;
		}
	}
}
void fonk(int sayi){
	int a,b,c;
	int i;
	int toplam=0;
	a=sayi/100;
	b=(sayi/10)%10;
	c=sayi%100;
	if(((a*a*a)+(b*b*b)+(c*c*c))==sayi){
		printf("armstrong");
	}
	for(i=1;i<=sayi;i++){
		if(sayi%i==0){
			toplam+=i;
			if(toplam==sayi){
				printf("mukemmel sayi");
			}
		}

	}
	if(asalmi(sayi)==1){
		printf("asal");
	}
	else if ((a*a*a)+(b*b*b)+(c*c*c)!=sayi && toplam!=sayi && asalmi(sayi)==0){
		printf("hicbiri degil");
	}
}
int main(int argc, char *argv[]) {
	int sayi;
	puts("sayi girin:");
	scanf("%d",&sayi);
	fonk(sayi);
	return 0;
}






