# SpaceX Data Analysis Project
# Aperçu du projet
Ce répertoire regroupe l'ensemble des résultats du projet d'analyse de données SpaceX réalisé dans le cadre du projet IBM Capstone. L'objectif de ce projet est d'analyser et de prédire pour une hypothétique société de fusées "SpaceY" qui veut se lancer sur le marché des vols spaciaux, les performances des lancements de SpaceX en utilisant les données fournies par l'API SpaceX et les techniques de web scraping. Les résultats tirés de cette analyse ont pour but d'optimiser les stratégies opérationnelles de "SpaceY" afin de proposer un prix concurenciel sur le marché des vols spaciaux.
# Contenus
Dans ce répertoire, vous trouverez 8 fichiers IPYNB présentant les résultats de cette analyse, de la collecte de donnée à l'analyse prédictive.
# Introduction
Dans ce travail, nous allons prédire si le premier étage de la fusée Falcon 9 atterrira avec succès. SpaceX annonce les lancements de la fusée Falcon 9 sur son site web, avec un coût de 62 millions de dollars ; d'autres fournisseurs coûtent plus de 165 millions de dollars chacun, une grande partie des économies est due au fait que SpaceX peut réutiliser le premier étage. Par conséquent, si nous pouvons déterminer si le premier étage atterrira, nous pouvons déterminer le coût d'un lancement. Cette information peut être utilisée si une autre entreprise souhaite faire une offre à SpaceX pour le lancement d'une fusée. 
# Méthodologie
#### • Collecte de données :
Les données ont été collectées à l'aide de l'API SpaceX et du web scraping avec une magnifique bibliothèque de soupes.
#### • Analyse de données
Analyse exploratoire des données (EDA) à l'aide de la visualisation et de SQL.
#### • Visualisation des données
Utilisation de Folium pour cartographier les sites de lancement des fusées de SpaceX
#### • Analyse prédictive 
Développer et tester des modèles qui prédisent les résultats des atterrissages.
# Conclusion
Sur la base de l'analyse, les conclusions suivantes peuvent être tirées :
• Un nombre plus élevé de vols sur un site de lancement est corrélé à un taux de réussite accru.

• Site de lancement-CCAFS SLC 40 convient au lancement de fusées dont la masse de charge utile varie de faible
à très haut

• Les orbites qui ont un taux de réussite élevé sont ES-L1, HEO, SSO et GEO

• Le modèle le plus efficace à prédire la réussite du lancement d'une fusée est l'arbre de décision avec une précision de 0,94.
# Annexe
• Les directives et la configuration des notebooks partagés ont été élaborées et sont détenues par IBM.

• Les données utilisées dans ce projet ont été obtenues via l'API SpaceX et via du web scraping sur la page wikipedia présentant le projet falcon9.
