#include<stdio.h>
void main()
{
    int a,b;
    char c;
    
    scanf("%c",&c);
    scanf("%d %d",&a,&b);
    
    switch(c)
    {
        case '+':c=a+b;
        break;
        
        case '-':c=a-b;
        break;
        
        case '*':c=a*b;
        break;
        
        case '/':c=a/b;
        break;
        
        case '%':c=a%b;
        break;
        
        default:
               printf("invaild option");
        
    }
    printf("%d",c);
}
