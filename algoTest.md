SI condition----------------------------------------------------------------> booleen vrai ou faux
                                                                                

    ALORS 
        blocs d'instructions --->VRAI
    SINON
        blocs d'instructions--->FAUX
    FINSI



    SI score>15
                                                                                

    ALORS 
        AFFICHER "J'ai mangé plus de 1 pomme "
    SINON
        AFFICHER "J 'ai ma premiére pomme"
    FINSI


----------------------------------------exemple 2----------------------------------------------------

Si score =10 ALORS
        AFFICHER "j'ai mange ma premiére pomme"
FINSI
SI score = 20 ALORS
        AFFICHER "j'ai manger ma deuxiéme pomme"
FINSI
SI score = 30 ALORS
        AFFICHER "j'ai manger ma troisiéme pomme"
FINSI



Si score =10 ALORS
        AFFICHER "j'ai mange ma premiére pomme"

SI score = 20 ALORS
        AFFICHER "j'ai manger ma deuxiéme pomme"

SI score = 30 ALORS
        AFFICHER "j'ai manger ma troisiéme pomme"
        FINSI
    FINSI
FINSI

---------------------------------------------------------------------------------------------------------------------
ALGORITHME algoTest1                  |     algotest2
                                            variable
                                            nom chaine de caractere
variable                                    age=nombre entier
clef =booleen;                              sexe= booleen

Debut                                   | dEBUT
clef <- false                           | age <-age du personnage
                                        |
avance
tourneDroite
avance
clef<- true
tourneGauche
tourneGauche
avance
tourneDroite


si clef =true ALORS                     | si age > 20 
                                        |    ALORS
     avancer                            | avancer
                                        | SINON
                                        |         Afficher "je suis trop jeune"
                                        arret de l'algo
si  clef =false ALORS                   | si age>=28 
                                        |       ALORS
                                        |       avancer
    afficher la porte est fermé         |SINON
                                                AFFICHER "je suis trop jeune"
                                                arret de l'algo
                                                FINSI
                                                AVANCER
    FINSI
FINSI
avance  

Fin
---------------------------------------------------------------------------------------------------------------------
test multiple

Algorithme algotest3
VARIABLE
    age : ENTIER
    sexe :booleen

DEBUT
    age<-ageDuPersonnage
    sexe<-sexeDuPersonnage
    Si age>20 ET sexe = VRAI
    ALORS
        avancer
    SINON
        AFFICHER "je ne peux pas passer"
        arret de l'algo
    FINSI
FIN


Algorithme algotest4
VARIABLE
    age : ENTIER
    sexe :booleen

DEBUT
    age<-ageDuPersonnage
    sexe<-sexeDuPersonnage
    Si age>28 OU sexe = FAUX
    ALORS
        avancer
    SINON
        AFFICHER "je ne peux pas passer"
        arret de l'algo
    FINSI
FIN
------------------------------------------------------------------------------------------------------------
 ALGORITHME algotest5
 VARIABLE
    GROS : booleen
     
     DEBUT
        GROS<- VRAI
        avance
         si gros = vrai et touche boite  rouge
        affiche "aie"
        Grand <-FAUX
         FINSI
         tournerGauche
         avancer
         Si toucheTete ALORS
            AFFICHER "Youpy"
            grand<-VRAI
        FINSI
        tournerGAuche
        avancer
         Si toucheBoiteRouge ET grand = VRAI ALORS
             AFFICHER "aie"
             grand<-FAUX
        FINSI
        tournerDroite
        SI toucheBoiteRouge ET grand = VRAI ALORS
            AFFICHER "aie"
            grand<-FAUX
        SINON
            SI toucheBoiteRouge ET grand = FAUX ALORS
             affiche "ouille"
             Finsi
        Finsi
        tournerGauche 
        avncer

    FIN








    