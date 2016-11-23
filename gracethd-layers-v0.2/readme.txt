Readme GraceTHD-Layers

AVEC SPATIALITE
QGIS a beaucoup de difficultés à exploiter les vues complexes Spatialite. Comme son nom l'indique, attention gracethd-layers-v0.02_gracethd-mcd-v2.0_qgis2.12.3_postgis.qgs fonctionne avec 2.12.3. Ce projet ne fonctionne pas correctement avec qgis 2.8 ou 2.14. 

AVEC POSTGIS
Avec un éditeur de texte, dans le fichier gracethd-layers-v0.02_gracethd-mcd-v2.0_qgis2.12.3_postgis.qgs remplacer la chaine de caractères suivante par celle correspondant à vos paramètres :
	<datasource>dbname='gracethd20' port=5433 user='postgres' sslmode=disable
