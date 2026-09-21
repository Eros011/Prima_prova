# Prima_prova
Scrivere un programma in linguaggio c che chiede un numero in input che determina l'età di una persona , stampa se è maggiorenne o minorenne.

questo e una "prova"


# Titolo

**Questa è un prova**

-uno
-due
-tre
/******************************************************************************

Scrivi un programma in linguaggio C che richieda all'utente di inserire tre numeri interi. Il programma deve:
Verificare se tutti e tre i numeri sono positivi utilizzando l'operatore and.
Verificare se almeno uno dei numeri è pari utilizzando l'operatore or.
Verificare se nessuno dei numeri è maggiore di 100 utilizzando l'operatore not.
Il programma deve poi stampare messaggi appropriati in base alle verifiche effettuate.

*******************************************************************************/
#include <stdio.h>

int main()
{
    int numero;
    printf("Dimmi tre numeri interi: ");
    scanf("%d %d %d" , &numero &numero &numero);
    
    if(numero > 0 && numero > 0 && numero > 0){
    printf("I numeri che hai inserito sono positivi.\n");
    }
     else{
          printf("Non tutti i numeri che hai inserito sono positivi.\n");
     }
    if(numero % 2 == 0 || numero % 2 == 0 || numero % 2 == 0){
        printf("almeno uno dei numeri che hai inserito e pari");
    }
     else{
        printf("Non tutti i numeri che hai inserito sono pari"); 
     }
    if(!(numero < 100 || numero < 100 || numero < 100)){
        printf("Nessuno dei numeri che hai inserito e pari");
    }
     else{
         printf(" almeno uno dei numeri che hai inserito e pari");
     }
     
    return 0;
}
