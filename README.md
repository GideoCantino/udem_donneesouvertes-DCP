# HNU 6055 : Données ouvertes — Été 2025
Université de Montréal : Centre de recherche interuniversitaire en Humanités Numériques (CRIHN)

Cours suivi dans le cadre du **Microprogramme en humanités numériques**, dans le but d'acquérir de nouvelles compétences en matière d'analyse de données et de gestion de jeux de données.

**TRAVAIL FINAL** : travail de manipulation des données contenues dans l'une des tables de la BEdT, ou _Bibliografia Elettronica dei Trovatori_ "une base de données relationelle consacrée à la poésie lyrique des troubadours, première étape de la création d'un corpus informatisé de toute la poésie lyrique européenne du Moyen Age (auteurs, textes, métrique, manuscrits, bibliographie moderne)" (BEdT v.2.5, "Homepage").

**CRediT** : « Les données contenues dans la bibliographie peuvent être consultées librement et utilisées dans des publications en mentionnant le numéro de la version, visible sur chaque écran, et la date de la dernière mise à jour de la base de données. » (BEdT v.2.5, "Homepage"; trad. Cantú Patiño, 2025).

**Direction scientifique** : Stefano Asperti
**Direction technique** : Luca De Nigro

Shield : [![CC BY 4.0][cc-by-shield]][cc-by]

Cette œuvre est mise à disposition selon les termes de la
[licence Creative Commons Attribution 4.0 International][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: https://creativecommons.org/licenses/by/4.0/deed.fr
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg

# MÉTHODOLOGIE DE RECHERCHE
Dans cet exercice j'ai cherché uniquement à manipuler des données extraites de la BEdT à partir de l'une de ses tables (sur 132) : il s'agit du tableau TESTI_NEI_CANZONIERI_PROVENZALI (textes dans les chansonniers provençaux), qui regroupe tous les noms et codes des textes troubadouresques, ainsi que quelques informations additionnelles dont le genre poétique auquel ils se rattachent. 

## Source de donnees:
Asperti, Stefano, « Testi nei canzonieri provenzali », Bibliografia Elettronica dei Trovatori (BEdT), 2012, URL : http://www.bedt.it/. Attribution (CC-BY 4.0)

Date d'extraction : 9 mai 2025

# Prétraitement des données

J'ai converti le dossier original CVS en dossier Excel ; je n'ai opéré aucune modification afin de conserver les données intactes (et par manque de temps également).

# Dossiers

## Données
- **TESTI_NEI_CANZONIERI_PROVENZALI.xlsx** : fichier original contenant toutes les données sans modifications, avec les informations suivantes par colonne :
  - **repertorio_n** : **numéro de répertoire** des textes selon la classification Pillet-Casterns (000,000)

## Figures
**2025_05_15_DCP_BEdT_textes_chansonniers_histogramme.png** : histogramme effectué à partir des données du tableau dynamique.

## Resultats
- **2025_05_15_DCP_BEdT_textes_chansonniers_frequences.xlsx** : continent les données sous forme de tableau dynamique, avec les genres poétiques en première colonne, et à côté de leur nombre d'occurrences par genre pour l'ensemble du corpus.

# Licence

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
