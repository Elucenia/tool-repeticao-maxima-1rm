<!-- ELUCENIA technical documentation · repeticao-maxima-1rm · fr · no clinical/professional/rights approval -->

# 1RM estimée (Epley et Brzycki)

[conditions, sources et autorisations](https://elucenia.org/fr/outils/repeticao-maxima-1rm)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Charge soulevée

`carga`

kg · intervalle: 1–500

### Répétitions complètes jusqu’à l’échec

`reps`

intervalle: 1–15

## Édition de la méthode

Epley charge×(1+rép/30) et Brzycki 1993 charge×36/(37−rép); moyenne locale; 1 rép=charge

## Formule documentée

Epley: 1RM = charge × (1 + répétitions/30).

Brzycki: 1RM = charge × 36 ÷ (37 − répétitions).

Le résultat principal est la moyenne des deux. Avec 1 répétition, la charge est la 1RM.

## Limites et population

La 1RM est une estimation à partir de la charge en kg et des répétitions complètes jusqu’à la fatigue, et non un maximum mesuré. LeSuer 1997 a étudié 67 étudiants non entraînés, après familiarisation, au développé couché, au squat et au soulevé de terre, avec des séries de 10 répétitions ou moins. L’interface accepte jusqu’à 15, mais cette étude ne justifie pas une extrapolation à 11–15. L’erreur variait selon l’exercice. La moyenne Epley–Brzycki est un choix local, pas une équation combinée validée dans cette étude ; le résultat ne garantit pas une charge maximale sûre.

## Références

- [Brzycki M. Strength testing: predicting a one-rep max from reps-to-fatigue. J Phys Educ Recreat Dance, 1993.](https://doi.org/10.1080/07303084.1993.10606684)

- [LeSuer DA et al. The accuracy of prediction equations for estimating 1-RM performance in the bench press, squat, and deadlift. J Strength Cond Res, 1997.](https://doi.org/10.1519/00124278-199711000-00001)

- [LeSuer1997,JStrengthCondRes11(4):211–213](https://paulogentil.com/pdf/The%20Accuracy%20of%20Prediction%20Equations%20for%20Estimating%201-RM%20Performance%20in%20the%20Bench%20Press,%20Squat,%20and%20Deadlift.pdf)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Résultats documentés

Les informations ci-dessous conservent les sorties de la méthode pour des exemples synthétiques. Elles ne constituent pas une validation clinique indépendante.

### 1

Epley 133,3 kg · Brzycki 133,3 kg

| Détails du résultat | |
| --- | --- |
| 90% de 1RM (force maximale) | 120,0 kg |
| 80% de 1RM (hypertrophie/force) | 106,7 kg |
| 70% de 1RM | 93,3 kg |
| 60% de 1RM (débutants, endurance) | 80,0 kg |


### 2

Epley 93,3 kg · Brzycki 90,0 kg

| Détails du résultat | |
| --- | --- |
| 90% de 1RM (force maximale) | 82,5 kg |
| 80% de 1RM (hypertrophie/force) | 73,3 kg |
| 70% de 1RM | 64,2 kg |
| 60% de 1RM (débutants, endurance) | 55,0 kg |


### 3

Epley 60,0 kg · Brzycki 60,0 kg

| Détails du résultat | |
| --- | --- |
| 90% de 1RM (force maximale) | 54,0 kg |
| 80% de 1RM (hypertrophie/force) | 48,0 kg |
| 70% de 1RM | 42,0 kg |
| 60% de 1RM (débutants, endurance) | 36,0 kg |

