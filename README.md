# begingJhipster

# Démarrer avec JHipster

Bienvenue dans le guide de démarrage rapide de JHipster! JHipster est une plateforme de développement pour générer, développer et déployer des applications Spring Boot + Angular/React/Vue dans un seul package.

## Prérequis

Avant de commencer, assurez-vous que vous avez installé Node.js sur votre machine. Vous pouvez télécharger la dernière version de Node.js sur [https://nodejs.org/](https://nodejs.org/).

## Installation

Suivez ces étapes pour installer JHipster et créer votre première application.

1. Créez un nouveau répertoire pour votre projet et naviguez-y :

```bash
mkdir onlinestore && cd onlinestore
```

2. Installez JHipster globalement en utilisant npm :

```bash
npm install -g generator-jhipster
```

- En cas de problèmes, essayez d'installer une version spécifique de JHipster comme suit :

```bash
npm install -g jhipster/generator-jhipster#v7.x_maintenance
```

## Utilisation de JHipster

Après l'installation, vous pouvez utiliser les commandes suivantes pour commencer à travailler avec JHipster :

- Pour afficher l'aide et découvrir plus de commandes :

```bash
jhipster --help
```

- Pour créer une nouvelle application JHipster :

```bash
jhipster
```

- Pour importer un modèle JDL (JHipster Domain Language) dans votre projet, utilisez :

```bash
jhipster jdl ./jdl/jhipster-order-stock-jdl.jh
```

Assurez-vous que le fichier `.jh` se trouve dans le répertoire spécifié ou ajustez le chemin selon votre structure de répertoire.

## Prochaines étapes

Après avoir configuré votre projet JHipster, explorez les documents et ressources suivants pour tirer le meilleur parti de JHipster :

- [Documentation officielle de JHipster](https://www.jhipster.tech/documentation-archive/)
- [JHipster GitHub repository](https://github.com/jhipster/generator-jhipster)
- [Communauté JHipster sur Stack Overflow](https://stackoverflow.com/questions/tagged/jhipster)

# Commandes

```bash
# Créer un répertoire pour le projet et naviguer à l'intérieur
mkdir onlinestore && cd onlinestore

# Installer JHipster globalement
npm install -g generator-jhipster

# En cas de problèmes, installer une version spécifique de JHipster
npm install -g jhipster/generator-jhipster#v7.x_maintenance

# Afficher l'aide de JHipster
jhipster --help

# Créer une nouvelle application JHipster
jhipster

# Importer un modèle JDL dans le projet
jhipster jdl ./jdl/jhipster-order-stock-jdl.jh

# Compiler et exécuter l'application avec Maven Wrapper
./mvnw
```

## Contribution

JHipster est un projet open-source, et les contributions sont toujours les bienvenues! Si vous souhaitez contribuer, veuillez consulter le [guide de contribution](https://github.com/jhipster/generator-jhipster/blob/main/CONTRIBUTING.md) sur GitHub.
