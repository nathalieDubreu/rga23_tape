# rga23_tape

## Utiles
- Tous les programmes R liés à cette analyse sont disponibles dans le dossier Tape du repository [rga23](https://github.com/nathalieDubreu/rga23) 
- [Dictionnaire des variables et modalités du RGA](https://docs.google.com/spreadsheets/d/16DxQiRkNIRXOBTypMM7NZsaku60rkBLX/edit?usp=sharing&ouid=111896801001167457308&rtpof=true&sd=true)

## **Champ** : 
- Les exploitations éligibles au RGA 2023 en cultures ou en élevages respectant les seuils de la CAPL (400 points ou plus - cf. document PDF)
- Hors points liés aux 2,7 tonnes de coprah
- => 3094 unités

## Rappel des limites du RGA dans le cadre de l'analyse TAPE
- Seuls les chefs d'exploitations sont interrogés (pas les travailleurs) 
- Pas de déclinaison hommes/femmes dans les catégories et sous-catégories ni selon l'âge des travailleurs

## Catégories et sous-catégories traitées
    - Score allant de 0 à 4 selon les index
    - Code 55 -> exploitations non classées (acceptable jusqu'à 10% du nombre d'exploitations)
    - Code 99 -> exploitations non concernées

- [Diversité](1-Diversity.md)
    
| score | Diversite_1_Culture | Diversite_2_Animaux | Diversite_3_Arbres | Diversite_4_Activite |
|-------|----------------------|----------------------|---------------------|----------------------|
| 0     | 774                  | 2223                 | 411                 | 879                  |
| 1     | 231                  | 641                  | 486                 | 620                  |
| 2     | 321                  | 177                  | 51                  | 978                  |
| 3     | 1476                 | 53                   | 162                 | 336                  |
| 4     | 292                  | ---                  | 1984                | 238                  |
| 55    | ---                  | ---                  | ---                 | 43                   |

- [Synergies](2-Synergies.md)
      
| score | Synergies_1_Integration | Synergies_2_SolPlantes | Synergies_3_IntegrationArbres | Synergies_4_Connectivite |
|-------|-------------------------|------------------------|-------------------------------|--------------------------|
| 0     | 2475                    | 366                    | 441                           | 522                      |
| 1     | 182                     | 1736                   | 145                           | 1027                     |
| 2     | 57                      | 706                    | 1347                          | 959                      |
| 3     | 51                      | 108                    | 691                           | 378                      |
| 4     | 76                      | 7                      | 470                           | 208                      |
| 55    | 253                     | ---                    | ---                           | ---                      |
| 99    | ---                     | 171                    | ---                           | ---                      |

- [Efficience](3-Efficience.md)
 
| score | Efficience_1_Intrants | Efficience_2_Engrais | Efficience_3_Pesticides | Efficience_4_ProductiviteBesoins |
|-------|------------------------|----------------------|--------------------------|----------------------------------|
| 0     | 1031                   | 1922                 | 166                      | 906                              |
| 1     | 1521                   | 406                  | 339                      | 59                               |
| 2     | 222                    | 27                   | 43                       | 637                              |
| 3     | 167                    | 82                    | 36                       | 985                              |
| 4     | 60                      | 657                  | 2510                     | 507                              |
| 55    | 63                     | ---                  | ---                      | ---                              |

- [Recyclage](4-Recyclage.md)

| score | Recyclage_4_Energie    |
|-------|-----|
| 0     | 2939|
| 1     |   28|
| 2     |   25|
| 3     |   44|
| 4     |   58|

- [Culture et traditions alimentaires](6-CultureTraditions.md)

| score | CultureTraditions_1_regimeAlimentaire   |
|-------|-----|
| 0     | 41  |
| 1     | 219 |
| 2     | 1112|
| 3     | 1395|
| 4     | 327 |

- [Cocreation](7-Cocreation.md)

| score | Cocreation_1_Plateformes | Cocreation_2_AccesConnaissances | Cocreation_3_Participation |
|-------|--------------------------|---------------------------------|----------------------------|
| 0     | 1008                      | 170                             | 2132                       |
| 1     | 923                      | 227                             | 330                        |
| 2     | 621                    | 113                             | 281                        |
| 3     | 463                      | 2307                            | 189                        |
| 4     | 79                      | 79                              | 132                        |
| 55    | ---                     | 198                             | 30                         |


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

- 6.2 IDENTITÉ ET CONSCIENCE LOCALES OU TRADITIONNELLES (PAYSANNES/INDIGÈNES)
- 6.3 UTILISATION DE VARIETÉS/RACES LOCALES ET CONNAISSANCES TRADITIONNELLES (PAYSANNES / INDIGÈNES) POUR LA PRÉPARATION DES ALIMENTS
- 8.1 ÉMANCIPATION DES FEMMES
- 10.2 ORGANIZATIONS ET ASSOCIATIONS DE PRODUCTEURS
- 10.3 PARTICIPATION DES PRODUCTEURS DANS LA GOUVERNANCE DE LA TERRE ET DES RESSOURCES NATURELLES

