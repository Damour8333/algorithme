Selon faim ----------------------------------------------------------------------->Variable testée
       CAS 0 : AFFICHER "j'ai tres faim" 
       CAS 1 : AFFICHER "j'ai encore trés faim" 
       CAS 2 : AFFICHER "j'ai bien mangé" 
       CAS 3 : AFFICHER "je n'ai plus faim" 
       AUTREMENT : AFFICHER "ce cas n'existe pas"
    FINSELON 


    EXERCICES
    ALGORITHME algoSelon1
    VARIABLE 
            mois : ENTIER
    DEBUT
        SAISIR mois 
        SELON mois 
           CAS 1 : afficher "Janvier"
           CAS 2 : afficher "Février"
           ...
           CAS 12 : afficher "Décembre"
           AUTREMENT AFFICHER "ce mois n'existe pas"
        FINSELON
    
    FIN


    EXERCICES
    ALGORITHME algoSelon
    VARIABLE 
            jour : ENTIER
    DEBUT
        SAISIR jour
        SELON jour
           CAS 1 : afficher "lundi"
           CAS 2 : afficher "mardi"
           ...
           CAS 7: afficher "vendredi"
           AUTREMENT AFFICHER "ce mois n'existe pas"
        FINSELON
    
    FIN