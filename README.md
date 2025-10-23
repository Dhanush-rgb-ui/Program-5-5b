# Module-5 Day-2 SEB
## AIM:
To write a C program to calculate the Product of first 12 natural numbers using Recursion

## For example:
<img width="250" height="75" alt="image" src="https://github.com/user-attachments/assets/b25aee48-3220-48e2-bccc-0e2ee2399b35" />

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
<img width="515" height="77" alt="image" src="https://github.com/user-attachments/assets/24dbd58f-7a77-4329-b351-e6a02fef909d" />

