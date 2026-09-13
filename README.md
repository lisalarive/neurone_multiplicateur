# neurone_multiplicateur

Petit projet réalisé en 2023, lorsque j'étais élève au lycée Simone Veil, avec l'aide d'un étudiant de l'École des Ponts et Chaussées (ENPC).

## Présentation

L'objectif du projet était de découvrir le fonctionnement d'un neurone artificiel à travers un exemple simple en Python.

Le neurone est entraîné à partir de plusieurs données afin d'apprendre à reproduire la fonction :

**f(x, y) = 2x + 3y**

Le programme ajuste progressivement les poids du neurone en fonction de l'erreur entre le résultat attendu et le résultat calculé.

## Fonctionnement

Le programme :

1. définit plusieurs données d'entraînement ;
2. initialise les poids du neurone ;
3. calcule une sortie à partir des entrées et des poids ;
4. mesure l'erreur entre la sortie obtenue et la sortie attendue ;
5. ajuste les poids ;
6. répète cet entraînement un grand nombre de fois ;
7. utilise ensuite le neurone entraîné pour effectuer une nouvelle prédiction.

Une fonction de vérification permet également de comparer le résultat obtenu avec le calcul mathématique attendu.

## Exemple

Pour les valeurs :

```text
x = 3
y = 7
