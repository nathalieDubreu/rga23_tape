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
    - 4 sous catégories : DONE
  
| score | Diversite_1_Culture | Diversite_2_Animaux | Diversite_3_Arbres | Diversite_4_Activite |
|-------|----------------------|----------------------|---------------------|----------------------|
| 0     | 774                  | 2223                 | 411                 | 879                  |
| 1     | 231                  | 641                  | 486                 | 620                  |
| 2     | 321                  | 177                  | 51                  | 978                  |
| 3     | 1476                 | 53                   | 162                 | 336                  |
| 4     | 292                  | ---                  | 1984                | 238                  |
| 55    | ---                  | ---                  | ---                 | 43                   |

- [Synergies](2-Synergies.md)
    - Sous catégories 2.2 : DONE
      
| score | Synergies_1_Integration | Synergies_2_SolPlantes |
|-------|-------------------------|------------------------|
| 0     | 2475                    | 366                    |
| 1     | 182                     | 1736                   |
| 2     | 57                      | 706                    |
| 3     | 51                      | 108                    |
| 4     | 76                      | 7                      |
| 55    | 253                     | ---                    |
| 99    | ---                     | 171                    |

- [Efficience](3-Efficience.md)
    - 4 sous catégories : DONE
 
| score | Efficience_1_Intrants | Efficience_2_Engrais | Efficience_3_Pesticides | Efficience_4_ProductiviteBesoins |
|-------|------------------------|----------------------|--------------------------|----------------------------------|
| 0     | 1087                   | 2256                 | 166                      | 906                              |
| 1     | 1625                   | 158                  | 199                      | 59                               |
| 2     | 106                    | 14                   | 63                       | 637                              |
| 3     | 204                    | 9                    | 44                       | 985                              |
| 4     | 9                      | 657                  | 2622                     | 507                              |
| 55    | 63                     | ---                  | ---                      | ---                              |

- [Recyclage](4-Recyclage.md)
    - Sous catégorie 4.4 ENERGIE RENOUVELABLE (UTILISATION ET PRODUCTION)

| score | Recyclage_4_Energie    |
|-------|-----|
| 0     | 2939|
| 1     |   28|
| 2     |   25|
| 3     |   44|
| 4     |   58|

- [Cocreation](7-Cocreation.md)
    - Manque la sous catégorie 7.1 PLATEFORMES POUR LA CRÉATION ET LE TRANSFERT HORIZONTAL DE CONNAISSANCES ET DE BONNES PRATIQUES (plus de 1700 exploitations encore à classer)

| score | Cocreation_1_Plateformes | Cocreation_2_AccesConnaissances | Cocreation_3_Participation |
|-------|--------------------------|---------------------------------|----------------------------|
| 0     | 180                      | 170                             | 2132                       |
| 1     | 465                      | 227                             | 330                        |
| 2     | 534                      | 114                             | 281                        |
| 3     | ---                      | 2319                            | 189                        |
| 4     | ---                      | 66                              | 132                        |
| 55    | 1915                     | 198                             | 30                         |


- [Gouvernance](10-Gouvernance.md)
    - DONE (1 seule sous-catégorie à traiter via les données du RGA)

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

