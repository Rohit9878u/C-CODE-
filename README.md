# C-CODE-

#include <stdio.h>
int main(){
    int i= 0;
    printf("enter the number 0 to 10");
    while(i<=10);
   printf("%d", i);
    i++;
}

#include <stdio.h>
int main(){
 int i=10;
   printf("enter the number 10 to 0");
   while(i>=0){
        printf("%d", i);
        i--;
    }
    return 0;


#include <stdio.h>
int main(){
  int i=10;
    printf ("enter the value of 10 to 0");
    while(i>=0){
      printf("%d", i);
        i--;
    }
 
}

#include <stdio.h>

int main() {
   short a;
    long long b;
    printf("Enter a short integer and a long long integer: ");
    scanf("%hd %lld", &a, &b);

    
    if (a == 0) {
    printf("Division by zero error. Exiting program.\n");
      return 1;
    }

  
   printf("Addition (a + b): %lld\n", (long long)a + b);
   printf("Subtraction (b - a): %lld\n", b - (long long)a);
   printf("Multiplication (a * b): %lld\n", (long long)a * b);
  printf("Division (b / a): %lld\n", b / (long long)a);

    return 0;



#include <stdio.h>

int main() {
    short a;
    long long b;
    
    scanf("%hd %lld", &a, &b);

    if (a == 0) {
        
        return 1;
    }
    else{

    printf("%lld\n", a + b);
    printf("%lld\n", b - a);
    printf("%lld\n", a * b);
    printf("%lld\n", b / a);
    }

    return 0;
}









    
    
    
    
    

