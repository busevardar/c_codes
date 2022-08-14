#include <stdio.h>
#include <stdlib.h>
#include <string.h>

//stringteki toplam kelime sayısını veren program
int wrd(char s[]){
	int i=0;
	int toplam=1;
	for(i=0;s[i]!='\0';i++){
		if(s[i]==' ' || s[i]=='\n' || s[i]=='\t'){
		toplam+=1;
	}
	}
	return toplam;
}
int main(){
	char s[100];
	puts("cumle gir:");
	gets(s);
	printf("%d",wrd(s));
	return 0;
}



//stringi tersine cevirip yazdıran program
void terscevir(char s1[]){
	int i,uzunluk;
	uzunluk=strlen(s1);
	char temp;
	for(i=0;i<uzunluk/2;i++){
		temp=s1[i];
		s1[i]=s1[uzunluk-1-i];
		s1[uzunluk-1-i]=temp;
	}
	printf("%s",s1);
}

int main(){
	char s1[100];
	puts("cumle gir:");
	gets(s1);
	puts("cumlenin tersi:");
	terscevir(s1);
	return 0;
	
}




//string harflerinin arasına boşluk ekleyen program

void boslukekleme(char s1[]){
	int i=0;
	while(s1[i]!='\0'){
		printf("%c",s1[i]);
		printf(" ");
		i++;
	}
}
int main(){
	char s1[100];
	puts("kelime girin:");
	gets(s1);
	boslukekleme(s1);
}



//cumledeki karakter sayılarını ayrı ayrı veren program 

void f(char s[]){
	int digit=0;
	int letter=0;
	int special=0;
	int i;
	for(i=0;s[i]!='\0';i++){
		if(s[i]==' ' || s[i]=='\n' || s[i]=='\t' || s[i]=='.' || s[i]==',' ){
			special+=1;
		}
		else if(s[i]>='0' && s[i]<='9'){
			digit+=1;
		}
		else{
			letter+=1;
		}
	}
	printf("ozel karakter sayisi= %d \n",special);
	printf("numara sayisi= %d \n",digit);
	printf("harf sayisi= %d \n",letter);	
	
}



//iki stringi karsılastırma

int f(char s1[], char s2[]){
	int i;
	int uzunluk;
	uzunluk=strlen(s1);
	if(strlen(s1)!=strlen(s2)){
		return 0;
}
	else{
		for(i=0;s1[i]!='\0';i++){
			if(s1[i]!=s2[i]){
				return 0;
}
}
}
return 1;
}
int main(){
	char s1[100],s2[100];
	puts("cumle gir");
	gets(s1);
	puts("cumle gir");
	gets(s2);
	if(f(s1,s2)==0){
		printf("ayni degil");
	}
	else if(f(s1,s2)==1){
		printf("ayni");
	}
	return 0;
	}



//HARFLERİ BÜYÜTÜP KÜÇÜLTEN PROGRAM//
void upper(char a[]){
	int i;
	for(i=0;a[i]!='\0';i++){
		if(a[i]>=97 && a[i]<=122){
			a[i]-=32;
		}
	}
}

void lower(char a[]){
	int i;
	for(i=0;a[i]!='\0';i++){
		if(a[i]>=65 && a[i]<=90){
			a[i]+=32;
		}
	}
}

int main(){
	char name[20];
	printf("isim giriniz:");
	gets(name);
	lower(name);
	printf("%s",name);
	return 0;
}


// STRİNG SONUNA STRİNG EKLEME
void mystrcat(char *str1,const char *str2,int n){
	int i,j;
	while(str1[i]!='\0'){
		i++;
	}
	for(j=0;j<n;j++){
		str1[i]=str2[j];
		i++;
	}
	str1[i]='\0';
}

int main(){
	char name1[20],name2[20];
	printf("isim1:");
	gets(name1);
	printf("isim2:");
	gets(name2);
	mystrcat(&name1,&name2,20);
	printf("eklenen sonuc: %s",name1);
	return 0;
}




void mystrcpy(char str1[], char str2[],int n){
	int i,j;
	for(i=0;i<n;i++){
		str1[i]=str2[i];
	}
	i++;
	str1[i]='\0';
}


int main(){
	char name1[20],name2[20];
	printf("isim1:");
	gets(name1);
	printf("isim2:");
	gets(name2);
	mystrcpy(name1,name2,20);
	printf("sonuc: %s",name1);
	return 0;
}




//strcmp fonk

	int mystrcmp(char *s1,char *s2){
		int i=0;
		int uzunluk=strlen(s2);
		while(i<uzunluk){
			if(s1[i]<s2[i]){
				return -1;
			}
			else if(s1[i]>s2[i]){
				return +1;
			}
			i++;
		}
		if(i==uzunluk){
			if(s1[i]==s2[i]){
				return 0;
			}
		}
	}


int main(){
	char name1[30],name2[30];
	printf("isim1:");
	gets(name1);
	printf("isim2:");
	gets(name2);
	int a=mystrcmp(name1,name2);
	printf("%d\n",a);
	if(a==1){
		printf("%s stringi %s den önce gelir",name2,name1);
	}
	else if(a==-1){
		printf("%s stringi %s den sonra gelir",name2,name1);
	}
	else{
		printf("stringler ayni");
	}
	
	return 0;
}




//mystrncmp
	int mystrncmp(char *s1,char *s2,int n){
		int i=0;
		
		while(i<n){
			if(s1[i]<s2[i]){
				return -1;
			}
			else if(s1[i]>s2[i]){
				return +1;
			}
			i++;
		}
		if(i==n){
			if(s1[i]==s2[i]){
				return 0;
			}
		}
	}


int main(){
	int n=2;
	char name1[30],name2[30];


	printf("isim1:");
	gets(name1);
	printf("isim2:");
	gets(name2);
	int a=mystrncmp(name1,name2,n);
	
	if(a==1){
		printf("%s stringi %s den önce gelir",name2,name1);
	}
	else if(a==-1){
		printf("%s stringi %s den sonra gelir",name2,name1);
	}
	else{
		printf("stringler ayni");
	}
	
	return 0;
}



//ters ceviren program
void reverse(char *a,int n){
	int i,j;
	int uzunluk=strlen(a);
	char temp[n];
	for(i=uzunluk-1,j=0 ; i>=0,j<n ; i--,j++){
		temp[j]=a[i];
	}
	j++;
	temp[j]='\0';
	strncpy(a,temp,n);
	
}

int main(){
	char a[20]="buse sena vardar";
	int n=20;
	reverse(a,n);
	printf("%s",a);
	return 0;
}



