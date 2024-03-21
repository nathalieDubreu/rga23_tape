# rga23_tape

## Utiles
- Tous les programmes R liés à cette analyse sont disponibles dans le dossier Tape du repository [rga23](https://github.com/nathalieDubreu/rga23) 
- [Dictionnaire des variables et modalités du RGA](https://docs.google.com/spreadsheets/d/16DxQiRkNIRXOBTypMM7NZsaku60rkBLX/edit?usp=sharing&ouid=111896801001167457308&rtpof=true&sd=true)

## **Champ** : 
- Les exploitations éligibles au RGA 2023 en cultures ou en élevages respectant les seuils de la CAPL (400 points ou plus)
- Hors points liés aux 2,7 tonnes de coprah
- => 2825 unités

## Rappel des limites du RGA dans le cadre de l'analyse TAPE
- Seuls les chefs d'exploitations sont interrogés (pas les travailleurs) 
- Pas de déclinaison hommes/femmes dans les catégories et sous-catégories ni selon l'âge des travailleurs

## Catégories et sous-catégories traitées
    - Score allant de 0 à 4 selon les index
    - Code 5 -> exploitations non classées (acceptable jusqu'à 10% du nombre d'exploitations)
    - Code 9 -> exploitations non concernées

- [Diversité](1-Diversity.md)
    - 4 sous catégories : DONE
  
| score | Diversite_1_Culture | Diversite_2_Animaux | Diversite_3_Arbres | Diversite_4_Activite |
|-------|---------------------|---------------------|--------------------|----------------------|
| 0     | 575                 | 1958                | 259                | 598                  |
| 1     | 223                 | 637                 | 409                | 520                  |
| 2     | 295                 | 177                 | 50                 | 947                  |
| 3     | 1453                | 53                  | 156                | 330                  |
| 4     | 279                 | NA                  | 1951               | 236                  |
| 9     | NA                  | NA                  | NA                 | 194                  |

- [Synergies](2-Synergies.md)
    - Sous catégories 2.2 : DONE
      
| score | Synergies_1_Integration | Synergies_2_SolPlantes |
|-------|-------------------------|------------------------|
| 0     | 2206                    | 303                    |
| 1     | 181                     | 1562                   |
| 2     | 57                      | 679                    |
| 3     | 52                      | 103                    |
| 4     | 76                      | 7                      |
| 5     | 253                     | NA                     |
| 9     | NA                      | 171                    |

- [Efficience](3-Efficience.md)
    - Manque la sous catégorie 3.1 UTILISATION D’INTRANTS EXTERIEURS (1045 exploitations encore à classer)
 
| score | Efficience_1_Intrants | Efficience_2_Engrais | Efficience_3_Pesticides | Efficience_4_ProductiviteBesoins |
|-------|------------------------|----------------------|-------------------------|-----------------------------------|
| 0     | 631                    | 2063                 | 153                     | 786                               |
| 1     | 1048                   | 149                  | 194                     | 55                                |
| 2     | 59                     | 12                   | 59                      | 575                               |
| 3     | 37                     | 8                    | 29                      | 920                               |
| 4     | 5                      | 593                  | 2390                    | 489                               |
| 5     | 1045                   | NA                   | NA                      | NA                                |
   
- [Recyclage](4-Recyclage.md)
    - Sous catégorie 4.4 ENERGIE RENOUVELABLE (UTILISATION ET PRODUCTION)

| score | Recyclage_4_Energie    |
|-------|-----|
| 0     | 2692|
| 1     |   25|
| 2     |   22|
| 3     |   33|
| 4     |   53|

- [Cocreation](7-Cocreation.md)
    - Manque la sous catégorie 7.1 PLATEFORMES POUR LA CRÉATION ET LE TRANSFERT HORIZONTAL DE CONNAISSANCES ET DE BONNES PRATIQUES (1727 exploitations encore à classer)

| score | Cocreation_1_Plateformes | Cocreation_2_AccesConnaissances | Cocreation_3_Participation |
|-------|---------------------------|----------------------------------|----------------------------|
| 0     | 175                       | 162                              | 1927                       |
| 1     | 409                       | 217                              | 306                        |
| 2     | 501                       | 100                              | 257                        |
| 3     | NA                        | 2083                             | 165                        |
| 4     | NA                        | 64                               | 127                        |
| 5     | 1727                      | 186                              | 30                         |


## WIP
- [Questions en attente de retours](QuestionsPourLaDag.md)

## Catégories et sous-catégories Tape NON traitées via le RGA

- 6 CULTURE & TRADITIONS ALIMENTAIRES
- 8.1 ÉMANCIPATION DES FEMMES
- 10.2 ORGANIZATIONS ET ASSOCIATIONS DE PRODUCTEURS
- 10.3 PARTICIPATION DES PRODUCTEURS DANS LA GOUVERNANCE DE LA TERRE ET DES RESSOURCES NATURELLES

