# 1988
This is my first code.
#include<stdio.h>
int main(void){
    int n,i,rev=0;
    printf("enter positive number: ");
    scanf("%d",&n);
    while(n>=1){
        int i=n%10;
        rev=rev*10+i;
        n=n/10;
    }
    printf("rev = %d",rev);
    return 0;
}
