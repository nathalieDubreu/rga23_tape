# Questions en attente de retours de la DAG / FAO


## 5.2 MÉCANISMES DE RÉDUCTION DE LA VULNÉRABILITÉ	

| Niveau | Description                                                                                              | Critères                                                                    |
|--------|-------------|------------|
| 0 | Pas d’accès au crédit, pas d’assurance, pas de mécanismes de soutien communautaire. | Non à tout (8) |
| 1 | La communauté n’est pas très favorable et sa capacité à aider après les chocs est très limitée. Et / ou l’accès au crédit et à l’assurance est limité. | Accès uniquement au 2 |
| 2 | La communauté est solidaire mais sa capacité à aider après les chocs est limitée. Et / ou l’accès au crédit est disponible mais difficile à obtenir en pratique. L’assurance est rare et ne permet pas une couverture complète contre les risques. | Accès uniquement aux 3 et/ou 7 (+ éventuellement le 2) |
| 3 | La communauté est très solidaire aux hommes et aux femmes, mais sa capacité à aider après les chocs est limitée. Et / ou l’accès au crédit est disponible et l’assurance ne couvre que des produits / risques spécifiques. | Au moins deux parmi 1, 3, 5 et 6 mais pas 4 |
| 4 | La communauté soutient fortement les hommes et les femmes et peut apporter une aide significative après les chocs. Et / ou l’accès au crédit est quasi systématique et l’assurance couvre l’essentiel de la production. | Au moins le 4 |

- Il y a pas mal d'exploitations (888) qui ne sont pas classées avec ces filtres. 
    - Parmi ceux-là, 847 n'ont coché qu'une seule case :
        - 680 uniquement la case "Aide du pays" (5)
        - 90 uniquement "Défiscalisation" (6)
        - 77 uniquement "Crédits (accès facile)"
    - 41 ont coché 2 cases :

| score | AideProjets__1 (Crédits (accès facile)) | AideProjets__2 (Crédits (accès difficile)) | AideProjets__5 (Assurance) | AideProjets__6 (Indemnités calamités) | AideProjets__7 (Aide du pays) | n   |
|-------|----------------------------------------|------------------------------------------|-----------------------------|---------------------------------------|---------------------------------|-----|
| 55    | 0                                      | 0                                        | 1                           | 0                                     | 1                               | 8   |
| 55    | 0                                      | 1                                        | 0                           | 1                                     | 0                               | 3   |
| 55    | 0                                      | 1                                        | 1                           | 0                                     | 0                               | 27  |
| 55    | 1                                      | 0                                        | 0                           | 0                                     | 1                               | 2   |
| 55    | 1                                      | 1                                        | 0                           | 0                                     | 0                               | 1   |


- AideProjets : Etes-vous aidé pour vos projets par :
   - Crédits (accès facile)......1
   - Crédits (accès difficile)...2
   - Assurance...................3
   - Indemnités calamités........4 
   - Aide du pays................5
   - Défiscalisation.............6
   - Autres......................7
   - Aucune facilité.............8

## 8.2 TRAVAIL (CONDITIONS DE PRODUCTION, INÉGALITÉS SOCIALES)

| Niveau | Description | Critères |
|--------|-------------|----------|
| 0      | Les chaînes d’approvisionnement agricoles sont intégrées et gérées par l’agro-industrie. Il existe une distance sociale et économique entre les propriétaires fonciers et les travailleurs. Et/ou les travailleurs n’ont pas de conditions de travail décentes, font de bas salaires et sont très exposés aux risques. | Plus de 50% du temps = travail pénible ET utilisation de produits phyto chimiques OU glyphosate ET revenu ne couvre pas les besoins essentiels |
| 1      | Les conditions de travail sont difficiles, les travailleurs ont un salaire moyen pour le contexte local et peuvent être exposés à des risques. | Plus de 25% du temps = travail pénible ET utilisation de produits phyto chimiques OU glyphosate ET Besoins non satisfaits ou en tout cas pas d'économies réalisées |
| 2      | L’agriculture est principalement basée sur l’exploitation familiale mais les producteurs ont un accès limité aux capitaux et aux processus de prise de décision. Les travailleurs ont des conditions de travail décentes minimales. | Moins de 50 % ET Les revenus de votre production agricole vous permettent-ils de réaliser des économies ? = NON ET si produits phyto, il a eu la formation |
| 3      | L’agriculture est principalement basée sur l’exploitation familiale et les producteurs (hommes et femmes) ont accès au capital et aux processus décisionnels. Les travailleurs ont des conditions de travail décentes. | Moins de 50 % ET Les revenus de votre production agricole vous permettent-ils de réaliser des économies ? = OUI ET si produits phyto, il a eu la formation |
| 4      | L’agriculture est basée sur des exploitations familiales qui ont pleinement accès au capital et aux processus de prise de décision en matière d’équité entre les sexes. Il existe une proximité sociale et économique entre agriculteurs et salariés. | Non pertinent en 2023 (chefs d'exploitations uniquement) |

| score | n    |
|-------|------|
| 0     | 30   |
| 1     | 109  |
| 2     | 399  |
| 3     | 897  |
| 55    | 1659 |

| PropTravailPenibleExpl | UtilisationGlyphosate | TypePhytosanit__1 | FormationPhytosanit | BesoinsSatisf | Economies | nombre |
|------------------------|-----------------------|-------------------|---------------------|---------------|-----------|--------|
| 1                      | 2                     | NA                | NA                  | 2             | NA        | 321    |
| 2                      | 2                     | NA                | NA                  | 2             | NA        | 263    |
| 3                      | 2                     | NA                | NA                  | 1             | 2         | 227    |
| 3                      | 2                     | NA                | NA                  | 1             | 3         | 204    |
| 3                      | 2                     | NA                | NA                  | 2             | NA        | 160    |
| 3                      | 2                     | NA                | NA                  | 1             | 1         | 74     |


