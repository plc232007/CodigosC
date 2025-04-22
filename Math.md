#include <stdio.h>

//This code shows the Fibonacci sequence.

int main () {
    
    int a, b, i, n, temp;
    printf ("How many elements will there be? ");
    scanf ("%d", &n);
    
    a = 0;
    b = 1;
    
    for (i = 0; i < n; i++){
        
        printf("%d    ", a);
        temp = a + b;
        a = b; 
        b = temp;
        
    }
    return 0;
}
