#include <stdio.h>

int main() {
    int n;
    printf("Enter your digit for spelling(0 to 9):");
    scanf("%d",&n);
    switch(n){
        case 0:{
            printf("%d = Zero");
            break;
        }
        case 1:{
            printf("%d = One",n);
            break;
        }
        case 2:{
            printf("%d = Two",n);
            break;
        }
        case 3:{
            printf("%d = Three",n);
            break;
        }
        case 4:{
            printf("%d = Four",n);
            break;
        }
        case 5:{
            printf("%d = Five",n);
            break;
        }
        case 6:{
            printf("%d = Six",n);
            break;
        }
        case 7:{
            printf("%d = Seven",n);
            break;
        }
        case 8:{
            printf("%d = eight",n);
            break;
        }
        case 9:{
            printf("Nine");
        }
    }
}
