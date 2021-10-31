# c-program-for-commercial-calculator

#include<stdio.h>
#include<conio.h>

void main()
{
    float a,b,ans;
    char (op);
    
    printf("Enter the value of a and b\n:");
    scanf("%f%c%f",&a,&op,&b);
    
        switch (op)
        {
        case'+':
        ans=a+b;
        printf("addition of two values is%f:",ans );
        break;
        
        case'-':
        ans=a-b;
        printf("subtraction of two values is%f:",ans );
        break;
        
        case'*':
        ans=a*b;
        printf("multiplication of two values is%f:",ans );
        break;
        
        case'/':
        
        ans=a/b;
        printf("division of two values is%f:",ans );
        break;
    
        default:
        printf("invalid operator");
        
        
        }
        
}
