# Projet DataMining - Groupe 7

## But du projet

Notre but dans ce projet est, à partir des simples coordonnées GPS et temporelles des trajets Uber d'une personne, de trouver des informations personnelles et valorisables.

Plus d'explications dans le pdf de rapport `Datamining.pdf`.


## Fichiers présents sur le git

 - `videos`: contient la vidéo finale et les parties séparées
 - `data`: contient les jeux de données:
   - `uber-rides-dataset.csv` est le jeu de données brutes
   - `resultats_api.csv` est le jeu de données enrichit avec l'API google
   - les autres sont les résultats des analyses de clustering. leur principale utilité est de les faire passer à Knime, pour visualiser sur une carte les plots (ce qui n'est pas immédiat en python)
 - `KNIME_project_uber_geo.knwf` est le projet Knime de la première exploration.
 - `Example Workflows` nous a été utile à titre de référence, il ne fait pas partie du projet et peut être ignoré
 - `python` contient les différents scipts et notebook
    - `GeoUber.ipynb` permet d'avoir recourt à l'API google et préparer les données
    - `Clustering_hierarchique_Spectral_MeanShift.ipynb` compare différents algorithmes de clustering
    - `analyseEntropy.ipynb` exploite la périodicité des mots clés
    

