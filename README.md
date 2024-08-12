# Extracteur d'événements La Décadanse

Ce script Python extrait automatiquement les événements de la semaine en cours du site web [La Décadanse](https://ladecadanse.darksite.ch/) et les sauvegarde dans un fichier Excel.

## Fonctionnalités

- Extraction des événements de la semaine en cours
- Collecte des informations détaillées pour chaque événement :
  - Nom de l'événement
  - Lieu
  - Date
  - Heure de début
  - Prix
  - URL de l'image (si disponible)
  - Description complète
- Sauvegarde des données dans un fichier Excel

## Prérequis

- Python 3.7+
- pip (gestionnaire de paquets Python)
- Un compte OpenAI avec une clé API valide

## Installation

1. Clonez ce dépôt ou téléchargez le script.

2. Installez les dépendances requises :
   ```bash
   pip install scrapegraphai pandas openpyxl python-dotenv 
  ```
3. Le script extraira les événements et créera un fichier Excel nommé `evenements.xlsx` dans le même répertoire.

## Configuration

Vous pouvez modifier les paramètres suivants dans le script :

- `graph_config`: Changez le modèle GPT si nécessaire (actuellement configuré sur "gpt-3.5-turbo").
- `prompt`: Modifiez les instructions d'extraction si vous souhaitez des informations différentes ou supplémentaires.
- `source`: Changez l'URL source si nécessaire.

## Dépannage

- Si vous rencontrez une erreur de dépassement de quota OpenAI, vérifiez votre utilisation sur la [plateforme OpenAI](https://platform.openai.com/).
- Assurez-vous que votre environnement virtuel est activé si vous en utilisez un.

## Contributions

Les contributions à ce projet sont les bienvenues. N'hésitez pas à ouvrir une issue ou à soumettre une pull request.

## Licence

[Insérez ici la licence de votre choix, par exemple MIT, GPL, etc.]

## Contact

[Vos informations de contact ou celles du mainteneur du projet]
