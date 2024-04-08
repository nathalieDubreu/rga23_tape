# EFFICIENCE - Critères d'affectations dans les sous catégories 

## 3.1 UTILISATION D’INTRANTS EXTERIEURS

### 3 types d'intrants présents dans le RGA sont pris en compte

#### A - Niveau d'auto-production des plants et des semences
- Moyenne tronquée de niveau d'auto-production entre les 2 en cas de présence
- Modalités possibles :
     - 0 à 10% du volume utilisé.......1
     - 10 à 25% du volume utilisé......2
     - 25 à 50% du volume utilisé......3
     - 50 à 75% du volume utilisé......4
     - Plus de 75% du volume utilisé...5
- La part d'auto-production des semences est majorée à 5 s'il n'y a que des semences auto-produites et/ou données par d'autres agriculteurs

#### B - Degré d'autonomie alimentaire des animaux
- Aliments pris en compte :
    - AutAlimAnimauxBasseCour : aliments des animaux de basse cour
    - AutAlimBovinsFourrage : fourrage des bovins
    - AutAlimCaprinsFourrage : fourrage des caprins
    - AutAlimEquidesFourrages : fourrage des équidés
    - AutAlimOvinsFourrage : fourrage des ovins
    - AutAlimPorcins : aliments des porcins
    - AutAlimPoules : aliments des poules pondeuses
- Modalités de réponses possibles
    - Plus de 90%.......................................1
    - 75% à moins de 90%................................2
    - 50% à moins de 75%................................3
    - 25% à moins de 50%................................4
    - Moins de 25%......................................5
    - Aucune autonomie (tout est acheté)................6
    - Sans objet, ce type d'aliment n'est pas utilisé...7
- Recalcul de 5 niveaux d'autonomie noté de 1 à 5 :
    - Au moins 75 % -> 5
    - De 50 à 75% (voire 90%) -> 4,
    - De 25 à 50% (voire 75%) -> 3,
    - De 1 à 25% (voire 50%) -> 2,
    - De 0 % (voire une partie jusqu'à 25%) -> 1
  
#### C - Niveau d’autonomie assuré à partir des énergies renouvelables produits sur l'exploitaiton
- Modalités 
    - Pas de production d'énergie renouvelable -> 1
    - 25% -> 2
    - 50% -> 3
    - 75% -> 4
    - 100% -> 5 

| Sous catégorie | Description                                                                                       | Filtre                                                |
|----------------|---------------------------------------------------------------------------------------------------|-------------------------------------------------------|
| 0              | Tous les intrants sont produits et achetés en dehors de l’agroécosystème.                       | Si animaux : aliments achetés exclusivement / Si semences : pas d'auto-production / Si plants : pas d'auto-production / Pas d'énergie renouvelable                           |
| 1              | La majorité des intrants sont achetés en dehors de l’agroécosystème.                             | Si animaux : autonomie alimentaire < 25% / Moyenne d'auto-production des plants et semences : moins de 25% / Pas d'énergie renouvelable ou ~ 25%               |
| 2              | Certains intrants sont produits au sein de l’agroécosystème ou échangés avec d’autres membres... | Si animaux : autonomie alimentaire entre 25% et 50% / Moyenne d'auto-production des plants et semences entre 25 et 50% / Energie renouvelable ~25% ou ~50%                   |
| 3              | La majorité des intrants sont produits au sein de l’agroécosystème ou échangés avec d’autres... | Si animaux : autonomie alimentaire entre 50% et 90% / Moyenne d'auto-production des plants et semences entre 50 et 75% / Energie renouvelable ~50% ou ~75%                    |
| 4              | Tous les intrants sont produits au sein de l’agroécosystème ou échangés avec d’autres membres... | Si animaux : aliments présents sur l'exploitaiton uniquement / Moyenne d'auto-production des plants et semences > 75% / Energie renouvelable ~100%                           |

### Calcul d'une note pour classer les 1075 exploitations restantes suite au passage des premiers filtres

| Energie renouvelable | Présence de plants et semences | Animaux dont on contrôle l'autonomie | Note tronquée à l'unité | Pénalité TODO si présence matériel spécifié |
|:---------------------:|:-------------------------------:|:-------------------------------------:|------------------------|:--------:|
|          X            |                X                |                   X                   | 0.15 * noteEnergie + 0.25 * noteAutonomieAlimentaireAnimaux + 0.60 * noteAutoproduction |          |
|         non           |                X                |                   X                   | 0.35 * noteAutonomieAlimentaireAnimaux + 0.65 * noteAutoproduction |    -1    |
|          X            |                X                |                 non                   |       0.35 * noteEnergie + 0.65 * noteAutoproduction       |          |
|          X            |               non               |                   X                   | 0.35 * noteEnergie + 0.65 * noteAutonomieAlimentaireAnimaux |          |
|         non           |               non               |                   X                   |       noteAutonomieAlimentaireAnimaux      |    -1    |
|         non           |                X                |                 non                   |              noteAutoproduction             |    -1    |


## 3.2 GESTION DE LA FERTILITÉ DU SOL

Pratiques prises en compte pour discriminer entre les catégories 0 et 1 : 
- Utilisation de plantes de services.............1
- Intercultures..................................2
- Amendements calciques..........................6
- Utilisation de micro-organismes du sol.........7
- OU jardins océaniens
- Ou agroforesterie

| Sous catégorie | Description | Filtre |
|--------|-------------|--------|
|   0    | Les engrais synthétiques sont utilisés régulièrement sur toutes les cultures et / ou prairies (ou aucun engrais n’est utilisé par manque d’accès, mais aucun autre système de gestion n’est utilisé). | Pas d'engrais ou uniquement "Engrais (ou amendements) de synthèse" ET aucune des pratiques considérées |
|   1    | Les engrais synthétiques sont utilisés régulièrement sur la plupart des cultures et certaines pratiques biologiques (par exemple le fumier ou le compost) sont appliquées à certaines cultures et / ou prairies. | (Pas d'engrais ou uniquement "Engrais (ou amendements) de synthèse" ET au moins une des pratiques considérées) OU (Engrais de synthèse + SOIT engrais minéraux bio SOIT engrais organiques) |
|   2    | Les engrais synthétiques ne sont utilisés que sur quelques cultures spécifiques. Des pratiques biologiques sont appliquées aux autres cultures et / ou prairies. | Engrais de synthèse + engrais minéraux bio + engrais organiques |
|   3    | Les engrais synthétiques ne sont utilisés qu’exceptionnellement. Une variété de pratiques biologiques sont la norme. | Engrais de synthèse + engrais minéraux bio + engrais organiques et au moins une pratique considérée |
|   4    | Aucun engrais synthétique n’est utilisé, la fertilité du sol est gérée uniquement à travers une variété de pratiques biologiques. | Aucun engrais de synthèse mais minéraux et/ou organiques |

## 3.3 GESTION DES PESTES ET DES MALADIES

| Sous catégorie | Description | Filtre |
|--------|-------------|--------|
|   0    | Les pesticides chimiques et les médicaments sont utilisés régulièrement pour la lutte contre les ravageurs et les maladies. Aucune autre gestion n’est utilisée. | Utilisation de produits phyto chimiques sur toutes les cultures/espèces |
|   1    | Les pesticides et médicaments chimiques sont utilisés pour une culture/un animal spécifique uniquement. Certaines substances biologiques et pratiques organiques sont appliquées sporadiquement. | Utilisation de produits phyto chimiques sur une partie des cultures/espèces |
|   2    | Les ravageurs et les maladies sont gérés par des pratiques biologiques, mais les pesticides chimiques sont utilisés seulement dans des cas spécifiques et très limités. | Utilisation de produits phyto chimiques sur une seule culture/espèce |
|   3    | Aucun pesticide ni médicament chimique n’est utilisé. Les substances biologiques sont la norme. | Utilisation uniquement de produits phyto biologiques |
|   4    | Aucun pesticide ni médicament chimique n’est utilisé. Les ravageurs et les maladies sont gérés par une variété de substances biologiques et de mesures de prévention. | Aucune utilisation de produits phyto |

## 3.4 PRODUCTIVITÉ ET BESOINS DU MÉNAGE

| Niveau | Description | Filtre |
|--------|-------------|--------|
|   0    | Les besoins du ménage ne sont pas satisfaits en nourriture ni en d’autres produits essentiels. | Réponse NON à la question "Vos besoins en nourriture et autres produits essentiels sont-ils satisfaits par votre production ou les revenus de votre production agricole ?" |
|   1    | La production ne couvre que les besoins alimentaires du ménage. Pas de surplus pour générer des revenus. | Réponse NON à la question "Les revenus de votre production agricole vous permettent-ils de réaliser des économies ?" + Pas de vente de produits ni végétaux ni animaux |
|   2    | La production couvre les besoins alimentaires du ménage et les excédents génèrent de l’argent pour acheter les produits essentiels mais ne permettent pas d’économiser. | Réponse NON à la question "Les revenus de votre production agricole vous permettent-ils de réaliser des économies ?" |
|   3    | La production couvre les besoins alimentaires du ménage et les excédents génèrent des liquidités pour acheter les produits essentiels et réaliser des économies sporadiques. | Réponse "Oui, de façon occasionnelle" à la question "Les revenus de votre production agricole vous permettent-ils de réaliser des économies ?" |
|   4    | Tous les besoins du ménage sont satisfaits, à la fois en nourriture et en espèces, pour acheter tous les produits nécessaires et pour avoir des économies régulières. | Réponse "Oui, de façon régulière" à la question "Les revenus de votre production agricole vous permettent-ils de réaliser des économies ?" |

