# aws-consumer-reviews
AWS Consumer Reviews
Projet ESGI - M1 IA & Big Data

Objectif
Collecter des avis consommateurs via scraping, les stocker sur AWS S3, les traiter via AWS Lambda et les visualiser avec Streamlit.

Technologies
Python
AWS EC2
AWS S3
AWS Lambda
AWS IAM
AWS CloudWatch
Streamlit
Architecture
Scraping → S3/raw → Lambda → S3/processed → Streamlit → Dashboard

Équipe
Abdelkrim
Shun
Koceila
Daouda
Maxime

## Conventions de commit

Les messages suivent le format `type: description` avec une description en
français, courte et à l'impératif ou à l'infinitif.

- `feat` : ajout d'une fonctionnalité.
- `fix` : correction d'un bug.
- `docs` : modification de la documentation.
- `refactor` : modification du code sans changement de fonctionnalité.
- `test` : ajout ou modification de tests.
- `chore` : maintenance ou configuration du projet.
- `ci` : modification de l'intégration continue.
- `style` : modification de la mise en forme sans changement de logique.

Exemple : `feat: ajouter la collecte des avis`.
