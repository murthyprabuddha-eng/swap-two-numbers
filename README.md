# swap-two-numbers

#swapping of two numbers in python
a=10
b=25
a,b=b,a

print(a) #output 25
print(b) #output 10

//swapping of two numbers in C

#include <stdio.h>

int main() 
{
    int a=10,b=25,temp;
    
    temp=a;
    a=b;
    b=temp;
   printf("the value of a is :%d\n",a);
   printf("the value of b is :%d\n",b);
    return 0;
}

//output:
the value of a is :25
the value of b is :10
