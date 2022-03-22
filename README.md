# Les-boucles
/*Dans notre cours on a 2 type du boucles , et 3 boucles .
Type 1 : Boucles avec des conditions . Dans ce type la boucle ne s'arrêt que la condition pose est fausse 
on a dans ce type il y 'a deux boucles 
1 ) while
syntax : while (condition){
         ......
         ...... 
         ......
}*/
//exemple : un programme qui affiche Hello jusqu'a la condition est fausse , alors si i>10 la boucle va terminer 
#include<stdio.h>
#include<stdlib.h>

int main() {
    int i;
    i = 1;
    while (i<=10){
        printf(" Hello \n");
        i++;
    }
    system ("pause");
    return 0;
}

2 ) do ... while
syntax : 
do{
    ......
    ......
    }while(condition);
//exemple : un programme qui affiche Hello jusqu'a la condition est fausse , alors si i>10 la boucle va terminer
#include<stdio.h>
#include<stdlib.h>

int main() {
    int i;
    i = 1;
    do{
        printf("Hello\n");
        i++;
    }while(i<=10);
    system ("pause");
    return 0;
}


/* type 2 : Boucle avec un conteur . Dans ce type la boucle ne ne s'arrêt que le conteur a terminer 
On an qu'une seule boucle se ce type (for)
syntax : 
for (initialisation ; condition ; incrémentation/décrémentation){
   ......
   ......
   ......
   } */
   //exemple : un programme qui affiche Hello jusqu'a la condition est fausse , alors si i>10 la boucle va terminer
   #include<stdio.h>
#include<stdlib.h>

int main() {
    int i;
    for (i=1 ; i<=10 ; i++){
        printf("Hello\n");
    }
    system ("pause");
    return 0;
}


CONCLUSION : toute ces boucle son valable dans toutes les cas , mais si on sait le nombre maximal des operation , ces mieu d'utiliser FOR .Et s'il y'a une condition 
specifique come l'egaliter ou l'existance d'un nombre ou caractere WHILE dans ce cas est plus pratique
   
