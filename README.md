# Module-5 Day-2 SEB
## AIM:
To write a C program to calculate the Product of first 12 natural numbers using Recursion

## For example:

## Program:
```c
#include<stdio.h>
int product(int n ,int start, int sum){
    if(start>n){
        return sum;
    }
    sum=sum*start;
    return product(n,start+1,sum);
}
int main(){
    int a=12;
   int mult = product(a,1,1);
    printf("Product is = %d",mult);
    return 0;
}
```
## Result:

