//  A ve B tamsayı değişkenlerinin değerlerini yer değiştiren program(A=3 B=5 girildikten sonra A=5 
//B=3 olarak yer değişmeli
# iki-tamsayi-yerdegistir

#include <stdio.h>

int main(){
int A,B;
printf("ilk sayiyi giriniz: ");
scanf("%d\n",&A);
printf("ikinci sayiyi giriniz: ");
scanf("%d\n",&B);

printf("A = %d\nB=%d\n",A,B);

int temp = A;
A = B;
B = temp;
printf("A = %d\nB=%d\n",A,B);

return 0;
}
