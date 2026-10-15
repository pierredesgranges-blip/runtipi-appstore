# App store RunTipi personnel

| App | Description |
|---|---|
| [AeroLog](apps/aerolog) | Carnet de vols (passager & équipage) avec import des traces KML Flightradar24 |

## Ajouter ce store à RunTipi

1. Pousser ce dossier dans un dépôt GitHub **public** (ex. `runtipi-appstore`).
2. RunTipi → **Paramètres → App Stores → Add App Store**, coller l'URL du dépôt.
3. Installer **AeroLog** depuis le store.

Pour publier une nouvelle version : changer le tag de l'image dans `docker-compose.yml`, incrémenter `tipi_version` et `version` dans `config.json`, pousser, puis **Update App Stores** dans RunTipi.
