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
### Répondre aux questions suivantes pour créer votre application

![image](https://github.com/hrhouma/begingJhipster/assets/10111526/ca73690a-fc74-413e-a86c-8dc9af49b8e3)
![image](https://github.com/hrhouma/begingJhipster/assets/10111526/5ec85c33-f3c5-48e9-8831-af70ff7118f8)
![image](https://github.com/hrhouma/begingJhipster/assets/10111526/42534685-e2ae-47bb-91b3-ecb7461545d8)

- Pour importer un modèle JDL (JHipster Domain Language) dans votre projet, utilisez :

```bash
jhipster jdl ./jdl/jhipster-order-stock-jdl.jh
```

Assurez-vous que le fichier `.jh` se trouve dans le répertoire spécifié ou ajustez le chemin selon votre structure de répertoire.

## Compiler et exécuter l'application avec Maven Wrapper
./mvnw

# Très important
Assurez-vous que les ports sont libres ! Par exemple, le port 8080 doit être libre et non pas utilisé par une autre application.
Sinon vous pouvez effectuer les changements dans les configurations !

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
# Étapes
1. Saisir http://localhost:8080/ 
2. S'authentifier ou créer un compte
![image](https://github.com/hrhouma/begingJhipster/assets/10111526/8a69fa18-6d6a-43aa-b3bc-1605e658febe)
3. Saisir admin/admin
![image](https://github.com/hrhouma/begingJhipster/assets/10111526/0b1e27ef-db8c-4f48-85cc-dd174dd484de)
4. Voir les entités
![image](https://github.com/hrhouma/begingJhipster/assets/10111526/d1f97c76-661f-4ece-b76f-af4da985767c)
5. CRUD
![image](https://github.com/hrhouma/begingJhipster/assets/10111526/49268ed1-c87a-40d1-b8b4-a88b2d7e6201)
6. Dans la partie Administration, vous avez la possibilité d'accéder àa la documentaion
![image](https://github.com/hrhouma/begingJhipster/assets/10111526/635af71f-d7c2-4408-b043-ba3e46ec10c3)
Page de Open API
![image](https://github.com/hrhouma/begingJhipster/assets/10111526/38080985-fb06-49e6-9edf-e550d0a1c672)
7. Accéder à la page de la base de données en mémoire H2
http://localhost:8080/h2-console/
![image](https://github.com/hrhouma/begingJhipster/assets/10111526/7aab369f-7c69-4e0c-8688-729d34a7a5eb)



## Contribution

JHipster est un projet open-source, et les contributions sont toujours les bienvenues! Si vous souhaitez contribuer, veuillez consulter le [guide de contribution](https://github.com/jhipster/generator-jhipster/blob/main/CONTRIBUTING.md) sur GitHub.
