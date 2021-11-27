# Rapport d'alternance
---

<p style="margin-top: 70%;">
Auteur : <strong>David Cornacchia</strong><br>
Période : <strong>Octobre 2020 - Décembre 2021</strong><br>
Dernière mise à jour : <strong>03/12/2021</strong>
</p>

<div style="page-break-after: always;"></div>

# Sommaire
---

1. Contexte
   1. Présentation
   2. Greentic
   3. Objectifs
2. Problématiques
   1. Missions
   3. Méthodes de travail
   4. Présentation d'une mission
3. Bilan
   1. Ce que j'ai appris
   2. Ce que j'ai mis en pratique
   3. Ce que j'ai apporté 

<div style="page-break-after: always;"></div>

# Contexte
---

## Présentation

Je m'appel David Cornacchia, je suis actuelement le parcours de formation Développeur d'application PHP Symfony en alternance.

## Greentic

Créée en 2007, Greentic est une agence web situé à Lyon. Elle est composé actuèlement de 4 personnes salariés. Parmis les prestations proposées par Greentic, les solutions e-commerce sous Prestashop représente une des plus importante.
En tant que développeur PHP/Symfony, mon travail consistait principalement au développement de modules pour le CMS Prestashop qui est basé sur le Framework Symfony. 

Etant salarié de Greentic au moment mon inscription sur le parcours de formation, j'ai donc effectué mon alternance dans cette même entreprise.

## Les objectifs 
### Technique

L'un des objectifs de cet alternance étaient de pouvoir en paralèlle de ma formation, pouvoir mettre en pratique et perfectionner mes compétences acquises dans le cadre de ma formation _( PHP, Symfony, conception, versionning, etc...)_ .

### Organisation

L'immersion en milieu professionnel m'a permis également de me familiariser avec les méthodes et l'organisation du travail au sein d'une agence web, comme par exemple la répartition des tâches en fonction des prioritées et d'une estimation de temps ou l'organisation d'une mise en production d'une application web.

<div style="page-break-after: always;"></div>

# Problématiques
---

Au cours de cette alternance j'ai été amené à devoir apporter une solutions à plusieurs problématiques. 
Parmis celles-ci, 

## Comment configurer efficacement un environement de développement ?

Dans le cadre de mon alternance j'ai été amené à travailler sur des applications web déjà existante et utilisant des technologies plus ou moins récentes. Il était donc nécessaire à chaque fois de pouvoir reproduire un environement de développement local le plus fidèle possible à l'environement de production (version PHP, MySql, Composer, NodeJs, etc...). 

## Comment intégrer une nouvelle fonctionnalitée a une application existante ?

Le développement de modules pour le CMS Prestashop composant la majeur partie de mes missions, je devais donc pour chacune d'elles concevoir une solution qui permettrait d'intégrer une ou plusieurs nouvelles fonctionnalités, tout en veillant à ne pas perturber le fonctionnement ou la maintenabilité du reste de l'application.
Il est donc nécessaire d'avoir une bonne connaissance de la structure de l'application afin d'orienter son développement de manière a respecter au maximum l'architecture de celle-ci pour l'implémentation de nouvelle fonctionnalités.

<div style="page-break-after: always;"></div>

# Missions
---

## Organisation du travail

Comme dans beaucoup d'agence, les tâches sont réparties sous formes tickets qui sont attribués à un ou plusieurs développeur.
Chacun se voit donc attribué un certains nombre de tickets qui correspondent à une tâche précise.

Pour la gestion de ces tickets, nous utilisons l'outil `Wrike`. Le développeur peut avec cet outils consulter la liste des tickets qui lui ont été attribuées.

<img src="img/wrike_tasks_list.png" alt="wrike_tasks_lists">

Chacun de ces tickets contient un certain nombre d'information sur le travail a effectuer :
- Titre
- Client/Projet
- Description
- Dates de début et de fin estimé
- Estimation du temps nécessaire
- Personnes a qui ce ticket a été attribué
- etc...

<img src="img/wrike_task_show.png" alt="wrike_task_show">

## Différentes technologies

On peut distinguer les tâches qui m'ont été confiés par les technologies utilisés.
Ces mission consistaient majoritairement à la création ou l'upgrade de modules __`Prestashop`__, mais pouvaient également porter sur le développement de __`Scripts PHP`__ (from scratch), d'application __`Symfony/Sylius`__, ou sur des modules __`Wordpress`__

<img src="img/tasks-pie-chart.png" alt="répartissiion des technologies">

## Présentation d'une mission
L'une des plus important projet sur lequel j'ai pus travaillé est un module de marketplace pour Prestashop. 

### Description

Comme son nom l'indique ce module à pour rôle de créer une place de marché sur lequel les utilisateurs peuvent proposer leur propres produits.
Le module devait proposer notament :
- Un menu de configuration du module dans le Back-Office natif du CMS
- Un espace d'administration destiné aux vendeur
- Des fonctionnalitées supplémentaires destinées à l'interactions entre les clients et les vendeurs.

### Gestion de projet

A partir du cahier des charges le projet a été découpé en plusieurs tickets. Pour la plupart, ces tickets correspondaient aux différentes sections des menus de configurations ou à une fonctionnalitée spécifique _( ex: page de gestion des transporteurs, affichage du nom du fournisseur sur la page produit )_.

<img src="img/gestion_projet.png" alt="gestion_projet">

Une fois le développement de la branche terminée, elle était fusionnée à la branche principale après avoir été validé par le responsable du projet _(review de code et test manuels)_.

<img src="img/gestion_projet_pr.png" alt="gestion_projet_pr">

### Fonctionnalitées développées

Au cours des 9 mois de développement de ce module, les fonctionnalités sur lesquelles j'ai été amené à travailler m'ont permis d'acquérir ou de perfectionner un certain nombre de compétences :

- Analyse du fonctionnement d’une application/structure existante.
- Intégration de fonctionnalités 
- Manipulation de données/fichiers sous différents formats (JSON, CSV, XML, image) en PHP.
- Génération dynamique de fichier PDF
- Envoi et traitement de requêtes AJAX





