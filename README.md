# Etude-de-marché
Analyse exploratoire des données et analyse multidimensionnelle (K-means, CAH, PCA) 

Notebook 1/2 - Préparation, nettoyage et analyse exploratoire des données
Contexte
La poule qui chante, une entreprise française d’agroalimentaire, souhaite se développer à l'international. Une première analyse des groupements de pays à cibler pour exporter des poulets est requise.

Une étude de marché plus approfondie sera menée ultérieurement.

Source des données
FAOSTAT : DisponibiliteAlimentaire_2017.csv, FAOSTAT_PIB.csv et Population_2000_2018 :
World Bank open data : EoDB2017 The World bank.xlsx

Choix des variables basé sur Les 6 critères d'une analyse PESTEL ; Politique, Économique, Légal, Sociologique, Environnemental et Technologique.
9 Variables relatives à la volailles on été  séléctionnées :

Economique :
la Disponibilité alimentaire en quantité (kg/personne/an)
Le ratio quantité volaille / quantité d'apport proteique animal total, calculé à partir des données des Disponibilités alimentaire
Disponibilité de protéines en quantité (g/personne/jour) - Abandonnée -
Le ratio proteine issus de volaille / quantité de proteines animales totales, calculé à partir des données Disponibilité de protéines - Abandonnée -
Production (Milliers de tonnes)
Importations - Quantité (Milliers de tonnes)
Exportations - Quantité (Milliers de tonnes)
PIB par habitant

Sociologique :
Population (Milliers de personnes)
Coefficient de croissance callculé sur les données de la table Population

Politique, Économique, Légal, Technologique :
index Ease of doing business EoDB 2017

L'indice de facilité à faire des affaires (EoDB) est un système de classement établi par la Banque mondiale. Le score d'une économie en matière de facilité de faire des affaires est exprimé sur une échelle de 0 à 100, où 0 représente la performance la plus faible et 100 la meilleure.

Le score est établi sur 10 caractéristiques :
Démarrer une entreprise
Obtenir un permis de construire
Obtenir de l'électricité
Enregistrer une propriété
Obtenir un crédit
Protéger les investisseurs minoritaires
Payer des impôts
Commercer au-delà des frontières
Exécuter des contrats
Résoudre l'insolvabilité
SOURCE = World Bank open data

Le critère environnemental sera envisagé dans l'analyse finale.

Notebook 1/2 - Préparation, nettoyage et analyse exploratoire des données
Notebook 2/2 - Analyses multidimentionelles : K-means, CAH et PCA
