# VoyagerEase-Microservice-Planification

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/voyagerease/microservice-planification)
[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

[![My Skills](https://skillicons.dev/icons?i=nestjs,typescript&perline=4)](https://skillicons.dev)

## Description

Ce référentiel héberge le code source et les ressources nécessaires pour le microservice de planification de voyages dans le cadre du projet VoyagerEase. Ce microservice, développé avec NestJS, suit les principes du Domain-Driven Design (DDD) pour garantir une conception orientée métier efficace et modulaire.

## Structure du Référentiel

### 1. Code Source

- **src/** : Contient le code source du microservice.
  - **modules/** : Les modules du microservice, organisés selon les domaines métier.
    - **voyage/** : Module responsable de la gestion de la planification de voyages.
      - **domain/** : Contient les entités, les valeurs-objets et les agrégats liés au domaine du voyage.
      - **application/** : Implémente les cas d'utilisation et les services d'application liés à la planification de voyages.
      - **infrastructure/** : Gère les détails d'implémentation spécifiques (bases de données, API externes, etc.).
  - **common/** : Contient les éléments partagés entre les modules, tels que les utilitaires, les middlewares communs, etc.

### 2. Documentation

- **docs/** : La documentation du microservice.
  - **api-spec.yaml** : Spécification OpenAPI décrivant les points de terminaison de l'API du microservice.
  - **user-guide.md** : Guide d'utilisation pour les développeurs intégrant le microservice.

### 3. Configuration

- **config/** : Les fichiers de configuration du microservice.
  - **config.yaml** : Configuration générale du microservice (paramètres, clés d'API, etc.).

### 4. Tests

- **tests/** : Les tests unitaires et les tests d'intégration du microservice.

### 5. Déploiement

- **deploy/** : Les scripts et les configurations nécessaires pour déployer le microservice.
  - **Dockerfile** : Fichier Docker pour la création d'une image contenant le microservice.
  - **kubernetes/** : Fichiers YAML pour le déploiement sur des clusters Kubernetes.

### 6. Dépendances

- **vendor/** : Les dépendances tierces du microservice, si elles ne sont pas gérées par un gestionnaire de paquets.

### 7. Contribuer

- **CONTRIBUTING.md** : Guide pour les contributeurs du microservice.

## Technologies Utilisées

- Langage de Programmation : Typescript
- Système de Gestion de Base de Données : [Nom du SGBD utilisé, par exemple, PostgreSQL, MongoDB]
- Outils de Build et de Gestion des Dépendances : npm ou yarn
- Outils de Test : Jest

## Architecture DDD

Le microservice est structuré en suivant les principes du Domain-Driven Design (DDD). Chaque module correspond à un domaine métier spécifique, et le code est organisé selon les concepts DDD tels que les entités, les valeurs-objets, et les agrégats.

## Auteur

Nom de l'équipe de développement ou du développeur principal.

## Licence

Licence sous laquelle le microservice est distribué, par exemple, MIT, Apache 2.0.
