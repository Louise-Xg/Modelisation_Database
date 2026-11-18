## Modelisation_Database

Dans le cadre de la formation DWWM.

Il s'agit d'un brief concernant la méthode Mérise.
Ce dépôt contient des captures d'écran pour différentes parties du brief : Les challenges 4.1 thème Harry Potter, 4.2 thème Harry Potter, 4.3 thème Harry Potter ainsi que l'activité thème SPA :

- `exo1_MCD.png` : Modèle Conceptuel des Données (MCD) appliqué à la recette de `potion`s avec les `ingredient`s associés.

- `exo2_MLD.png` : Modèle Logique des Données (MLD) de `exo1_MCD.png`.

- `exo3_part1.png `: Modèle Physique des Données (MPD) du MLD `exo2_MLD.png`, ici seulement les tables `potion` et `ingredient` ont été créés et leurs clefs primaires ont été définies.
- `exo3_part2.png` : La suite du MPD `exo3_part1.png`, ici la table associative `ingredient_potion` a été crée ainsi que sa clef primaire et les étrangères définies.

- `Activite_MCD_part1.png` : MCD appliqué au cas de la SPA.
- `Activite_MLD_part2.png` : MLD de `Activite_MCD_part1.png`.
- `Activite_newMCD_part3.png` : Mise à jour du MCD après l'ajout de nouveaux éléments.
- `Activite_newMLD_part3.png` : Mise à jour du MLD suivant `Activite_newMCD_part3.png`.

# Problèmes rencontrés :

1. Distinction des entités, attributs et cardinalités à partir des règles de gestion.
2. Le choix des cardinalités.
3. Rédaction adéquate des clefs primaires et étrangères dans les tables.
