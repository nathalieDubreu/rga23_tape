# rga23_tape

## Utiles
- Tous les programmes R liés à cette analyse sont disponibles dans le dossier Tape du repository [rga23](https://github.com/nathalieDubreu/rga23) 
- [Dictionnaire des variables et modalités du RGA](https://docs.google.com/spreadsheets/d/16DxQiRkNIRXOBTypMM7NZsaku60rkBLX/edit?usp=sharing&ouid=111896801001167457308&rtpof=true&sd=true)

## **Champ** : 
- Les exploitations éligibles au RGA 2023 en cultures ou en élevages respectant les seuils de la CAPL (400 points ou plus - cf. document PDF)
- Hors points liés aux 2,7 tonnes de coprah
- => 2812 unités

## Rappel des limites du RGA dans le cadre de l'analyse TAPE
- Seuls les chefs d'exploitations sont interrogés (pas les travailleurs) 
- Pas de déclinaison hommes/femmes dans les catégories et sous-catégories ni selon l'âge des travailleurs

## Catégories et sous-catégories traitées
    - Score allant de 0 à 4 selon les index
    - Code 55 -> exploitations non classées (acceptable jusqu'à 10% du nombre d'exploitations)
    - Code 99 -> exploitations non concernées

- [Diversité](1-Diversity.md)
    - 4 sous catégories : DONE
  
| score | Diversite_1_Culture | Diversite_2_Animaux | Diversite_3_Arbres | Diversite_4_Activite |
|-------|----------------------|----------------------|---------------------|----------------------|
| 0     | 574                  | 1948                 | 260                 | 674                  |
| 1     | 222                  | 634                  | 410                 | 580                  |
| 2     | 292                  | 177                  | 50                  | 957                  |
| 3     | 1443                 | 53                   | 156                 | 329                  |
| 4     | 281                  | -                    | 1936                | 236                  |
| 55    | -                    | -                    | -                   | 36                   |

- [Synergies](2-Synergies.md)
    - Sous catégories 2.2 : DONE
      
| score | Synergies_1_Integration | Synergies_2_SolPlantes |
|-------|--------------------------|------------------------|
| 0     | 2196                     | 305                    |
| 1     | 181                      | 1549                   |
| 2     | 57                       | 676                    |
| 3     | 51                       | 104                    |
| 4     | 75                       | 7                      |
| 55    | 252                      | -                      |
| 99    | -                        | 171                    |

- [Efficience](3-Efficience.md)
    - Manque la sous catégorie 3.1 UTILISATION D’INTRANTS EXTERIEURS (plus de 1000 exploitations encore à classer)
 
| score | Efficience_1_Intrants | Efficience_2_Engrais | Efficience_3_Pesticides | Efficience_4_ProductiviteBesoins |
|-------|------------------------|-----------------------|--------------------------|----------------------------------|
| 0     | 627                    | 2052                  | 153                      | 775                              |
| 1     | 1047                   | 148                   | 193                      | 55                               |
| 2     | 59                     | 12                    | 59                       | 574                              |
| 3     | 36                     | 8                     | 29                       | 921                              |
| 4     | 5                      | 592                   | 2378                     | 487                              |
| 55    | 1038                   | -                     | -                        | -                                |

- [Recyclage](4-Recyclage.md)
    - Sous catégorie 4.4 ENERGIE RENOUVELABLE (UTILISATION ET PRODUCTION)

| score | Recyclage_4_Energie    |
|-------|-----|
| 0     | 2681|
| 1     |   25|
| 2     |   22|
| 3     |   33|
| 4     |   53|

- [Cocreation](7-Cocreation.md)
    - Manque la sous catégorie 7.1 PLATEFORMES POUR LA CRÉATION ET LE TRANSFERT HORIZONTAL DE CONNAISSANCES ET DE BONNES PRATIQUES (plus de 1700 exploitations encore à classer)

| score | Cocreation_1_Plateformes | Cocreation_2_AccesConnaissances | Cocreation_3_Participation |
|-------|---------------------------|----------------------------------|-----------------------------|
| 0     | 175                       | 162                              | 1927                        |
| 1     | 409                       | 217                              | 306                         |
| 2     | 501                       | 100                              | 257                         |
| 3     | -                         | 2083                             | 165                         |
| 4     | -                         | 64                               | 127                         |
| 55    | 1727                      | 186                              | 30                          |

- [Gouvernance](10-Gouvernance.md)

| score | Gouvernance_1_Emancipation |
|-------|----------------------------|
| 0     | 351                        |
| 1     | 847                        |
| 2     | 440                        |
| 3     | 976                        |
| 4     | 468                        |
| 55    | 12                         |


## WIP
- [Questions en attente de retours](QuestionsPourLaDag.md)
- [Récapitulatif avancement](Recapitulatif.md)

## Catégories et sous-catégories Tape NON traitées via le RGA

- 6 CULTURE & TRADITIONS ALIMENTAIRES
- 8.1 ÉMANCIPATION DES FEMMES
- 10.2 ORGANIZATIONS ET ASSOCIATIONS DE PRODUCTEURS
- 10.3 PARTICIPATION DES PRODUCTEURS DANS LA GOUVERNANCE DE LA TERRE ET DES RESSOURCES NATURELLES

