# projet-c
#include <stdio.h>
#include <cs50.h>
#include <string.h> 

int main(void)

{
    int film = get_int("donnez votre age pour le film: ");
    
    
    const string filmCategorieEnfant[3]= {"l'age de glace 4", "happy feet", "pokemon le pouvoir est en toi"};
    const string filmCategorieAdos[3]= {"shazam", "TED 2", "The avengers"};
    const string filmCategorieAdulte[3]= {"The Shining", "La Nonne", "Conjuring"};
    
    
    
        if(film < 11)
    {
        printf("vous ne pouvez aller voir seulement les films de la catégorie enfant\n");
        for(film = 0 ; film < 1 ; film++)
        {
            char proposition = get_char ("voulez-vous voir l'age de glace 4?\n");
            if (proposition == 'o' || proposition == 'O')
            {
                printf("ok, cela vous fera 4euros s'il vous plait\n");
            }
            else if (proposition == 'n' || proposition == 'N')
            {
                char proposition2 = get_char ("voulez-vous voir happy feet?\n");
                if (proposition2 == 'o' || proposition2 == 'O')
                {
                    printf("ok, cela vous fera 4euros s'il vous plait\n");
                }
                else if (proposition2 == 'n' || proposition2 == 'N')
                {
                    char proposition3 = get_char ("voulez-vous voir pokemon le pouvoir est en toi?\n");
                    if (proposition3 == 'o' || proposition3 == 'O')
                    {
                        printf("ok, cela vous fera 4euros s'il vous plait\n");
                    }
                
                }
                
            }
        }
      
    }
    
    else if (film <= 17)
    
    {
        printf("vous pouvez aller voir les films de la categorie ado\n");
         for(film = 0 ; film < 1 ; film++)
        {
            char proposition = get_char ("voulez-vous voir shazam?\n");
            if (proposition == 'o' || proposition == 'O')
            {
                printf("ok, cela vous fera 4euros s'il vous plait\n");
            }
            else if (proposition == 'n' || proposition == 'N')
            {
                char proposition2 = get_char ("voulez-vous voir TED 2?\n");
                if (proposition2 == 'o' || proposition2 == 'O')
                {
                    printf("ok, cela vous fera 4euros s'il vous plait\n");
                }
                else if (proposition2 == 'n' || proposition2 == 'N')
                {
                    char proposition3 = get_char ("voulez-vous voir THE AVENGERS ?\n");
                    if (proposition3 == 'o' || proposition3 == 'O')
                    {
                        printf("ok, cela vous fera 4euros s'il vous plait\n");
                    }
                   
                
                    
                   
                
                }
                
            }
        }
        
    }
    
          else if(film >= 18)
    {
        printf("vous pouvez aller voir les catégories de film pour adulte\n");
        for(film = 0 ; film < 1 ; film++)
        {
            char proposition = get_char ("voulez-vous voir The Shining ?\n");
            if (proposition == 'o' || proposition == 'O')
            {
                printf("ok, cela vous fera 4euros s'il vous plait\n");
            }
            else if (proposition == 'n' || proposition == 'N')
            {
                char proposition2 = get_char ("voulez-vous voir la nonne?\n");
                if (proposition2 == 'o' || proposition2 == 'O')
                {
                    printf("ok, cela vous fera 4euros s'il vous plait\n");
                }
                else if (proposition2 == 'n' || proposition2 == 'N')
                {
                    char proposition3 = get_char ("voulez-vous voir conjuring ?\n");
                    if (proposition3 == 'o' || proposition3 == 'O')
                    {
                        printf("ok, cela vous fera 4euros s'il vous plait\n");
                    }
                   
                
                    
                   
                
                }
                
            }
        }
    }
    
    
   
    
}
