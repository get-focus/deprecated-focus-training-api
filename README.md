# focus-training-api
API pour le training FOCUS

## Installation

Cloner le projet en local :

```bash
git clone https://github.com/get-focus/focus-training-api.git
```

Installer les dépendances du projet :

```bash
npm install
```

## Lancer l'API

```bash
npm start
```

## Utiliser l'API : liste des services

Les services disponibles sont les suivants :

| METHOD  | URL                    |
| ------- | ---------------------- |
| GET     | /movies/:id            |
| GET     | /movies/:id/actors     |
| GET     | /movies/:id/cameramen  |
| GET     | /movies/:id/directors  |
| GET     | /movies/:id/producers  |
| GET     | /movies/:id/writers    |
| PUT     | /movies/:id            |

| METHOD  | URL                    |
| ------- | ---------------------- |
| GET     | /persons/:id           |
| GET     | /persons/:id/movies    |
| PUT     | /persons/:id           |

Vous pouvez les tester dans votre navigateur, en saisissant par exemple :
```
http://localhost:9999/movies/10053
```
