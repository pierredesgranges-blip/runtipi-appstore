# App store RunTipi personnel

| App | Description |
|---|---|
| [AeroLog](apps/aerolog) | Carnet de vols (passager & équipage) avec import des traces KML Flightradar24 |

## Ajouter ce store à RunTipi

1. Remplacer `VOTRE_COMPTE` par votre identifiant GitHub dans `apps/aerolog/docker-compose.yml` et `apps/aerolog/config.json`
   (`sed -i 's/VOTRE_COMPTE/monlogin/g' apps/aerolog/*.json apps/aerolog/*.yml`).
2. Pousser ce dossier dans un dépôt GitHub **public** (ex. `runtipi-appstore`).
3. RunTipi → **Paramètres → App Stores → Add App Store**, coller l'URL du dépôt.
4. Installer **AeroLog** depuis le store.

Pour publier une nouvelle version : changer le tag de l'image dans `docker-compose.yml`, incrémenter `tipi_version` et `version` dans `config.json`, pousser, puis **Update App Stores** dans RunTipi.
