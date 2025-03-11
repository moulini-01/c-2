//# c-2
//max and min
#include<stdio.h>
#include<stdlib.h>
int main(){
    int a=-22,b=4;
    int maximum=(a+b+abs(a-b))/2;
    int minimum=(a+b-abs(a-b))/2;
    printf("max=%d\n",maximum);
    printf("min=%d\n",minimum);
    return 0;
}
