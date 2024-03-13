# rga23_tape

## Utiles
- Tous les programmes R liés à cette analyse sont disponibles dans le dossier Tape du repository [rga23](https://github.com/nathalieDubreu/rga23) 
- [Dictionnaire des variables et modalités du RGA](https://docs.google.com/spreadsheets/d/16DxQiRkNIRXOBTypMM7NZsaku60rkBLX/edit?usp=sharing&ouid=111896801001167457308&rtpof=true&sd=true)

## **Champ** : 
- Les exploitations éligibles au RGA 2023 en cultures ou en élevages respectant les seuils de la CAPL
- Hors unités interrogées initialement au titre de la coprahculture

## Questions en attente de retours de la DAG

## 2.2 Gestion du système sol-plantes

| Niveau | Description |
|--------|-------------|
|   0   Le sol est nu après la récolte. Pas de culture intercalaire. Aucune rotation des cultures (ou systèmes de pâturage en rotation). Perturbation importante du sol (biologique, chimique ou mécanique).  | Aucune culture OU monoculture |
|   1   Moins de 20 pour cent des terres arables sont couvertes de résidus ou de cultures de couverture. Plus de 80 pour cent des cultures sont produites en monoculture continue (ou sans pâturage en rotation).  | Aucune des pratiques (1,2,5) |
|   2   50 pour cent du sol est recouvert de résidus ou de cultures de couverture. Certaines cultures sont tournées ou intercalées (ou un pâturage en rotation est effectué).  | Au moins une des 3 pratiques + plusieurs cultures basses + la surface de pâturages (entre 0 et 50%) |
|   3   Plus de 80 pour cent du sol est recouvert de résidus ou de cultures de couverture. Les cultures sont alternées régulièrement ou intercalées (ou le pâturage en rotation est systématique). La perturbation du sol est minimisée.  | Au moins une des 3 pratiques + plusieurs cultures basses + la surface de pâturages (entre 50 et 80%). Pas de labour |
|   4   Tout le sol est couvert de résidus ou de cultures de couverture. Les cultures sont tournées régulièrement et les cultures intercalaires sont courantes (ou le pâturage en rotation est systématique). Peu ou pas de perturbation du sol.  | Au moins une des 2 pratiques + plusieurs cultures basses + la surface de pâturages (entre 50 et 80%). Pas de labour |

La colonne de droite correspond à ce que la DAG a indiqué comme filtres.

**Pour info :**
- Moins de 300 exploitants ont déclaré des pâturages ;
- 1037 exploitations déclarent faire une des 3 techniques suivantes :
  - Utilisation de plantes de services.............1
  - Intercultures..................................2
  - Paillage (plastique ou naturel)................5

Avec les filtres proposés, voici le classement :

| Score | Nombre d'exploitations |
|-------|------------------------|
|   0   |          377           |
|   1   |          1165           |
|   2   |           93           |
|  3-4  |            0           |
| Non classées |      332       |

=> **Quelles variables prendre en compte au-delà de ces 3 techniques et des cultures fourragères (y compris pâturages) trop minoritaires pour servir de base aux filtres...**

## Catégories et sous-catégories traitées

- Score allant de 0 à 4 selon les index
- Code 5 -> exploitations non classées
- Code 9 -> exploitations non concernées
    
- [Diversité](1-Diversity.md)
    - 4 sous catégories : DONE
  
| score | Diversite_1_Culture | Diversite_2_Animaux | Diversite_3_Arbres | Diversite_4_Activite |
|-------|----------------------|---------------------|--------------------|----------------------|
| 0     | 377                  | 1886                | 234                | 403                  |
| 1     | 210                  | 405                 | 267                | 462                  |
| 2     | 284                  | 151                 | 48                 | 891                  |
| 3     | 1448                 | 48                  | 152                | 326                  |
| 4     | 171                  | NA                  | 1789               | 228                  |
| 9     | NA                   | NA                  | NA                 | 180                  |

- [Efficience](3-Efficience.md)
    - Manque la sous catégorie 3.1 UTILISATION D’INTRANTS EXTERIEURS (939 exploitations encore à classer)
 
| score | Efficience_1_Intrants | Efficience_2_Engrais | Efficience_3_Pesticides | Efficience_4_ProductiviteBesoins |
|-------|------------------------|-----------------------|--------------------------|----------------------------------|
| 0     | 552                    | 1778                  | 148                      | 668                              |
| 1     | 918                    | 142                   | 179                      | 49                               |
| 2     | 50                     | 11                    | 54                       | 509                              |
| 3     | 25                     | 8                     | 24                       | 831                              |
| 4     | 6                      | 551                   | 2085                     | 433                              |
| 5     | 939                    | NA                    | NA                       | NA                               |

- [Recyclage](4-Recyclage.md)
    - Uniquement la sous catégories 4.4 ENERGIE RENOUVELABLE (UTILISATION ET PRODUCTION)

| score | Recyclage_4_Energie    |
|-------|------|
| 0     | 2375 |
| 1     | 22   |
| 2     | 17   |
| 3     | 23   |
| 4     | 53   |
