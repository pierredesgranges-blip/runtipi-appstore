# AeroLog

Carnet de vols personnel auto-hébergé, pensé pour les passagers **et** le personnel navigant.

## Fonctionnalités

- **Rôles** : passager, équipage (avec fonction à bord : CDB, OPL, CCP, PNC…) ou MEP (mise en place)
- **Saisie assistée** : recherche d'aéroports (IATA/OACI/ville), compagnies et types d'avion ; durée calculée automatiquement en tenant compte des fuseaux horaires
- **Trajectoires Flightradar24** : import des fichiers KML (ou CSV) téléchargés sur Flightradar24, trace colorée par altitude, profil altitude/vitesse interactif
- **Pré-remplissage depuis le KML** : aéroports, date, heures, n° de vol, indicatif, compagnie
- **Import groupé** : un vol créé automatiquement par fichier KML déposé
- **Carte** de tous les vols (orthodromies ou traces réelles) et **statistiques** : années, aéroports, compagnies, liaisons, avions, immatriculations, pays, records
- **Cartes vectorielles** MapLibre + OpenFreeMap (sombre, Fiord, clair, Liberty, Bright), vue globe
- **Reprise depuis FlightLog** (perdian/flightlog) : import direct des exports JSON ou XML
- **Sauvegarde** : export/import JSON (traces incluses) et CSV

## Configuration

- *Mot de passe d'accès* : protège l'interface (recommandé si l'app est exposée).
- Les données sont stockées dans une base SQLite dans `app-data/aerolog/data/`.
