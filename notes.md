### Notes 

Premières idées : on a la date, on peut plot la température, pression en fonction du temps
abscisses possibles : temps, géographie (département, ville, commune)

On peut se focus sur température, pression, vent, précipitation, neige

On pourra peut-être faire une map sur la fin 


Correlation entre : pression/vent, pression/temperature, etc -> croiser toutes les valeurs

KPIs Thermiques
Température
Amplitude thermique annuelle/mensuelle : Différence entre température max et min
Jours de gel/an : Nombre de jours où T° < 0°C
Jours de canicule : Nombre de jours où T° > 30°C
Température ressentie moyenne (avec vent et humidité)
Tendance de réchauffement : Évolution des températures moyennes sur 10 ans
:nuage_et_pluie: KPIs Hydrométriques

Précipitations
Intensité pluviométrique : mm/heure pendant les épisodes
Nombre de jours de pluie/an : Jours avec précipitations > 1mm
Périodes de sécheresse : Consécutifs jours sans pluie
Pluviométrie saisonnière : Répartition printemps/été/automne/hiver
Événements extrêmes : Jours avec précipitations > 95e percentile
:vitesse: KPIs Aérologiques

Vent
Vitesse moyenne du vent par saison
Direction dominante du vent (rose des vents)
Jours de vent fort : Vitesse > 60 km/h
Rafales maximales enregistrées
Index d'instabilité atmosphérique


KPIs Hygrométriques
Humidité et Pression
Humidité relative moyenne par saison
Jours de brouillard : Humidité > 95% + vent faible
Variations de pression : Amplitude quotidienne
Événements de forte pression : Pression > 1030 hPa
:usine: KPIs Géographiques et Temporels

Spatial
Gradient thermique Nord-Sud, Est-Ouest
Variabilité inter-stations : Coefficient de variation
Zones climatiques identifiées par clustering

Temporel
Saisonnalité : Amplitudes saisonnières
Tendances décennales : Évolution 2015-2025
Cycles diurnes : Variation jour/nuit
Événements météo rares : Fréquence des extrêmes


KPIs Composites et Indices
Indices climatiques
Indice de confort climatique : Température + humidité + vent
Indice de sécheresse : Précipitations - évapotranspiration
Indice de rigueur hivernale : Gel + vent + humidité
Score de variabilité météo : Coefficient de variation multi-variables

Corrélations croisées
Corrélation température-pression par saison
Corrélation vent-précipitations lors des tempêtes
Lag correlation : Précipitations vs pression (décalage temporel)

KPIs Business/Application
Agriculture
Jours de croissance : Température entre 5-30°C
Stress hydrique : Périodes sèches > 15 jours
Risque de gel tardif/printanier

Énergie
Jours de chauffage : Température < 15°C
Potentiel éolien : Vitesse vent > 10 m/s
Potentiel solaire : Jours sans nuages

Santé
Indice de pollution : Pression + vent + humidité
Jours de canicule avec seuils sanitaires
Comfort index : Température + humidité + vent


Ces KPIs vous permettront d'explorer votre dataset sous différents angles et de répondre aux exigences de votre projet (estimateurs, tests statistiques, régressions, PCA, clustering). Voulez-vous que je vous aide à implémenter certains de ces KPIs spécifiques ?