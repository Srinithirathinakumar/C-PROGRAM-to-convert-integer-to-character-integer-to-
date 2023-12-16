# C-PROGRAM-to-convert-integer-to-character-integer-to-
integer to character
#include<stdio.h>
int main(){  
    int n,sum=0,r;    
printf("enter the number=");    
scanf("%ld",&n);    
while(n>0)    
{    
r=n%10;    
sum=sum*10+r;    
n=n/10;    
}    
n=sum;    
while(n>0)    
{    
r=n%10;    
switch(r)    
{    
case 1:    
printf("one ");    
break;    
case 2:    
printf("two ");    
break;    
case 3:    
printf("three ");    
break;    
case 4:    
printf("four ");    
break;    
case 5:    
printf("five ");    
break;       
default:    
printf("tttt");    
break;    
}    
n=n/10;    
}    
return 0;  
}  
