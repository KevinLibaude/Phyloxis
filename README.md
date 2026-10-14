# Phyloxis

**Un launcher Android qui remet les intentions de l'utilisateur au centre de l'expérience mobile.**

Phyloxis est un projet de launcher Android inspiré de la philosophie de Windows Phone et Windows 10 Mobile, notamment de leurs tuiles dynamiques, de leur lisibilité et de leur simplicité d'utilisation.

Son ambition n'est pas de reproduire Windows 10 Mobile, mais d'en prolonger les principes à travers une expérience moderne, adaptée à Android.

Phyloxis propose une approche différente de l'écran d'accueil : plutôt que de placer les applications au centre de l'interface, il privilégie les **services, les intentions et les informations réellement utiles**.

> **Phyloxis propose, l'utilisateur dispose.**

## Vision

Les smartphones modernes offrent une multitude de fonctionnalités, mais leur utilisation repose essentiellement sur une succession d'applications, de notifications et d'interactions.

Phyloxis explore une autre approche :

- Accéder à une intention plutôt qu'à une application.
- Présenter les informations utiles au bon moment.
- Réduire les interactions superflues.
- Préserver la maîtrise de l'utilisateur sur son interface.
- Favoriser une expérience fluide, cohérente et prévisible.
- Limiter les sollicitations inutiles.

L'objectif est de retrouver la simplicité d'un téléphone centré sur l'essentiel, sans renoncer aux possibilités d'un smartphone moderne.

## Principes fondamentaux

### 1. Les services avant les applications

Phyloxis organise l'expérience autour de services représentant des intentions.

Les six services prévus pour la première version sont :

- **Communiquer** — Accéder aux échanges et aux moyens de communication.
- **Agenda** — Consulter et organiser ses événements.
- **Navigation** — Accéder aux déplacements et aux destinations.
- **Musique** — Retrouver et contrôler son expérience musicale.
- **Photos** — Accéder à ses contenus photographiques.
- **Courriers** — Consulter et gérer ses courriers électroniques.

Les applications restent accessibles directement à tout moment.

### 2. Des tuiles dynamiques

L'écran d'accueil repose sur des tuiles capables de représenter un service, une information ou une interaction.

Leur comportement s'adapte aux informations disponibles et aux besoins du service, tout en conservant une organisation stable.

L'utilisateur garde la maîtrise du placement et de l'organisation de ses tuiles.

### 3. Un gestionnaire d'attention

Toutes les informations ne méritent pas le même niveau d'attention.

Phyloxis distingue plusieurs niveaux d'expressivité :

- **Repos** — Présentation discrète.
- **Information** — Affichage d'une information utile.
- **Interaction** — Possibilité d'effectuer une action.
- **Prioritaire** — Mise en évidence d'un événement important.

Le système cherche à informer sans interrompre inutilement.

### 4. Des entités partagées

Les services peuvent exploiter des entités représentant des éléments du monde réel, notamment :

- Une personne.
- Un événement.
- Un lieu.

Ces entités permettent de maintenir une cohérence entre les services, sans fusionner arbitrairement les données issues de différentes applications.

### 5. Des connecteurs

Les connecteurs établissent le lien entre les services Phyloxis et les applications Android.

Un moteur de résolution détermine les applications compatibles avec une intention, en tenant compte des possibilités disponibles et des préférences explicites de l'utilisateur.

### 6. Des contextes

Phyloxis prévoit une gestion des contextes d'utilisation, notamment personnels et professionnels.

Un contexte permet d'adapter la présentation et la pertinence des informations sans imposer une réorganisation automatique de l'interface.

### 7. Le contrôle utilisateur

Phyloxis privilégie des comportements compréhensibles et prévisibles.

Le projet exclut notamment :

- La réorganisation automatique de l'écran d'accueil.
- Les widgets Android traditionnels comme fondement de l'interface.
- Les tutoriels obligatoires.
- Les changements de préférences effectués sans accord.
- Les animations purement décoratives ou intrusives.

## Interface utilisateur

L'interface s'appuie sur plusieurs éléments fondamentaux :

**Écran d'accueil**

Une organisation verticale de tuiles dynamiques, personnalisable par manipulation directe.

**Tiroir d'applications**

Une liste alphabétique inspirée de Windows 10 Mobile, avec navigation rapide par lettre et recherche.

**Barre d'état**

Une intégration visuelle cohérente avec Android et l'écran d'accueil.

**Navigation**

Une interaction pensée pour rester simple, directe et compatible avec les contraintes du système Android.

## Plateformes envisagées

Phyloxis est conçu prioritairement pour les smartphones Android.

Son architecture et son langage visuel doivent également permettre d'étudier une adaptation aux :

- Smartphones pliables.
- Tablettes.
- Environnements Android en mode bureau.

Ces adaptations font partie des perspectives du projet et ne constituent pas des fonctionnalités déjà livrées.

## Confidentialité

Phyloxis privilégie une approche respectueuse des données personnelles.

Les principes retenus comprennent :

- Le traitement local lorsque cela est possible.
- La limitation de la collecte de données.
- Le respect des autorisations Android.
- La transparence sur les interactions avec les applications.
- Le contrôle des préférences par l'utilisateur.

## Documentation

La conception fonctionnelle et les décisions structurantes sont documentées dans **Le Livre de Phyloxis**.

Ce document constitue la référence du projet pour :

- La vision produit.
- Les principes d'expérience utilisateur.
- L'architecture fonctionnelle.
- Le fonctionnement des services.
- Les mécanismes transversaux.
- Les règles d'interaction.
- Le langage visuel.
- Les décisions validées et les questions ouvertes.

Le développement doit s'appuyer sur cette documentation afin de conserver une cohérence entre la conception et l'implémentation.

## État du projet

**Statut : conception avancée et développement initial.**

Les travaux réalisés ou engagés comprennent notamment :

- La définition de la vision et des principes fondateurs.
- La conception du système de services.
- La définition des entités, connecteurs et contextes.
- La conception du gestionnaire d'attention.
- La création de l'identité visuelle et du logo.
- La création d'une première collection de fonds d'écran.
- La conception de planches d'interface et de composants.
- Les premiers travaux sur la manipulation des tuiles.

Les fonctionnalités décrites dans ce document ne sont pas nécessairement toutes implémentées.

## Philosophie

Phyloxis ne cherche pas à multiplier les fonctionnalités ni à automatiser chaque interaction.

Il cherche à proposer une interface capable de s'effacer lorsque l'utilisateur n'en a pas besoin et de devenir utile lorsqu'il la sollicite.

**Moins de distractions. Plus de sens. Plus de contrôle.**

---

**Phyloxis — Un accueil pensé autour de vous.**
