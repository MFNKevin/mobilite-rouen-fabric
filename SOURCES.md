# Sources

Toutes les données utilisées sont ouvertes. Sauf mention contraire, elles ont été téléchargées par les notebooks 00 et 01 le 20 octobre 2026.

| Source | Lien | Utilisée pour | Licence | Date |
| --- | --- | --- | --- | --- |
| INSEE, Filosofi 2021, carreaux de 200 m | https://www.insee.fr/fr/statistiques/8735162 | Population, âges, revenus, ménages et logement par carreau | Licence Ouverte 2.0 (Etalab), « Source : Insee » | 20/10/2026 |
| INSEE, projections de population Omphale 2018-2070 | https://www.insee.fr/fr/statistiques/6652134 | Population de la Seine-Maritime à l'horizon 2040 | Licence Ouverte 2.0 (Etalab), « Source : Insee » | 20/10/2026 |
| Arrêts de transport en France, transport.data.gouv.fr | https://www.data.gouv.fr/datasets/arrets-de-transport-en-france | Arrêts autour de chaque carreau (modèle), gares TER de Rouen | Licence Ouverte 2.0 | version du 13/01/2026, téléchargée le 20/10/2026 |
| GTFS du réseau Astuce, Métropole Rouen Normandie | https://transport.data.gouv.fr/datasets/donnees-statiques-et-temps-reel-du-reseau-astuce-metropole-rouen-normandie | Arrêts et lignes de métro, TEOR et bus | Licence Ouverte 2.0 | 20/10/2026 |
| GBFS Lovélo, Métropole Rouen Normandie | https://transport.data.gouv.fr/datasets/donnees-statiques-et-temps-reel-du-service-de-vls-lovelo-metropole-rouen-normandie | Les 126 stations de vélos en libre-service de Rouen | Licence Ouverte 2.0 | 20/10/2026 |
| GBFS Citiz, 15 réseaux | https://transport.data.gouv.fr/datasets?type=vehicles-sharing&q=citiz | Positions et capacités des 1 615 stations Citiz | Licence Ouverte | 20/10/2026 |
| Catalogue mondial des flux GBFS, MobilityData | https://github.com/MobilityData/gbfs/blob/master/systems.csv | Adresses des flux GBFS de Citiz et Lovélo | CC BY 3.0 | 19/10/2026 |
| IGN, ADMIN EXPRESS COG CARTO | https://geoservices.ign.fr/adminexpress | Contours des communes, de la Métropole de Rouen et de l'Eurométropole de Strasbourg | Licence Ouverte 2.0 (Etalab) | 20/10/2026, par le service WFS de la Géoplateforme |
| OpenStreetMap, extrait Geofabrik Haute-Normandie | https://download.geofabrik.de/europe/france/haute-normandie.html | Réseau des rues et chemins piétons (5 minutes = 400 m) | ODbL 1.0, © les contributeurs d'OpenStreetMap, données traitées par Geofabrik | extrait du 19/10/2026 |
| ADEME, Enquête nationale autopartage 2022, réalisée par 6t (communiqué du 22/09/2022) | https://www.ort.bourgogne-franche-comte.developpement-durable.gouv.fr/IMG/pdf/ademe_cp_autopartage_22092022.pdf | Une voiture en autopartage remplace 5 à 8 voitures personnelles | Citation | consulté le 20/10/2026 |
| Sujet du hackathon Epitech × Citiz × Microsoft | document remis aux équipes | 130 000 conducteurs et 2 800 voitures Citiz | | 19/10/2026 |

## Coûts des équipements (notebook 20)

| Équipement | Coût bas, moyen, haut (première année) | Sources |
| --- | --- | --- |
| Station Citiz | 20 000 €, 25 000 €, 32 000 € | Conseil municipal de Voreppe du 21/10/2021 (25 000 € par véhicule) ; prix moyen d'une voiture neuve en 2024, 36 700 € (Roole, AAA Data) ; livre blanc Citiz 2026 (aménagement de station minime) |
| Station de vélos | 13 000 €, 25 000 €, 35 000 € | Cerema, 2019 : 1 900 à 2 500 € HT par vélo en libre-service, station comprise (3 000 à 3 500 € pour un vélo à assistance électrique), 7 à 10 vélos par station |
| Arrêt de bus | 10 000 €, 15 000 €, 25 000 € | Cerema : environ 15 000 € TTC par point d'arrêt rendu accessible ; SDA-Ad'AP de Bourgogne-Franche-Comté : 10 000 € HT par arrêt ; abri voyageurs de 1 300 à 9 200 € |

Ces coûts sont des fourchettes, à confirmer avec Citiz et la Métropole. Les scénarios coûts bas et coûts hauts montrent combien d'emplacements un même budget finance selon la fourchette retenue.
