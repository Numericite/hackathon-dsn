# 👩‍💻 Employeur 360

## Description

Un outil facile et rapide pour suivre les coûts de la masse salariale de l'entreprise et obtenir des informations pertinentes sur les employés en deux clics.

## Problème

Les petites et moyennes entreprises passent du temps à agréger des données provenant de diverses sources (Excel, logiciels internes) pour préparer les réunions des dirigeants ou les entretiens avec les salariés. La déclaration sociale nominative est une source de données vérifiée qui pourrait permettre de créer des tableaux de bord automatiques, offrant ainsi un accès facile à des vues exploitables.

## Solution

Grâce à l'utilisation de l'ETL Logstash, de la base de données indexée Elasticsearch, et de l'outil de visualisation des données Kibana, voici les vues qui ont été créées :
* Vue entreprise : suivi de la masse salariale, des charges, et de l'égalité hommes-femmes dans l'entreprise.
* Vue focus salarié : accès aux informations détaillées sur le contrat, les salaires, et les primes d'un salarié.
* Vue comparative : comparaison de l'entreprise avec d'autres entreprises du même secteur ou d'autres secteurs.

## Impact envisagé

* Accéder sans actions internes à des données utiles pour le suivi et la prise de décision dans les petites et moyennes entreprises.
* Comparer en temps réel son activité avec celle d'autres entreprises similaires.

## [Facultatif] Retours sur la qualité des données exploitées

* Difficulté à suivre précisément les cotisations versées par l'employeur dans le jeu de donnée
