# Rapport d'alternance

<style>
   .img-container{
      display:flex; 
      justify-content:center;
   }
   .img-container>img{
      border: 3px solid grey;
   }
   .logo{
      height:50px;
      width:50px;
   }
   .sub-chap-img{
      height:100px;
   }
   .divider{
      height: 75px;
   }
</style>
<p style="margin-top: 70%;">
Auteur : <strong>David Cornacchia</strong><br>
Période : <strong>Octobre 2020 - Décembre 2021</strong><br>
Dernière mise à jour : <strong>03/12/2021</strong>
</p>

<div style="page-break-after: always;"></div>
<div align="center">

# Sommaire
</div>
<div class="divider"></div>

1. **Contexte**
   * Présentation

   * Greentic

   * Objectifs


2. **Problématiques**

   * Développer une fonctionnalité dans une application éxistante

   * Configurer un environement de développement


3. **Missions**

   * Organisation du travail

   * Méthodes de travail

   * Présentation d'une mission


4. **Bilan**

   * Ce que j'ai appris

   * Ce que j'ai mis en pratique

   * Ce que j'ai apporté 

   * Conclusion 

   * Après l'alternance 

<div style="page-break-after: always;"></div>

<div align="center">

# Contexte
</div>
<div class="divider"></div>

<img src="img/photo-david.jpg" class="sub-chap-img"><br>

## Présentation
Je m'appelle David Cornacchia, je suis actuellement le parcours de formation **Développeur d'application PHP Symfony** en alternance. 

J'ai commencé mon processus de reconversion professionnelle en 2018 en commençant par diverses formations courtes en ligne afin de m'initier au développement web, puis j'ai suivi le parcours OpenClassroom **Prep'fullstack**.

A l'issue de ce parcours j'ai trouvé un emploi de développeur back-end Junior au sein de la société Greentic qui tend à s'orienter de plus en plus vers des projets utilisant le framework **Symfony**. 

Mon désir de perfectionner mes compétences coïncidant avec la stragtégie d'évolution de la société, nous avons donc décidé de m'inscrire à parcours **Développeur d'application - PHP/Symfony** en alternance. 

<div class="divider"></div>
<img src="img/logos/greentic-logo.png" class="sub-chap-img"><br>

## Greentic
Créée en 2007, **Greentic** est une agence web située à Lyon. 

Elle est composée actuellement de 4 personnes. Parmis les prestations proposées par Greentic, les **solutions e-commerce** sous Prestashop représente une des plus importante.

En tant que développeur **PHP/Symfony**, mon travail consistait principalement au développement de modules pour le CMS **Prestashop** qui est basé sur le Framework Symfony. 

<div style="page-break-after: always;"></div>

<img src="img/target.jpg" class="sub-chap-img"><br> 

## Les objectifs
<div class="divider"></div>

### **Technique**

L'un des objectifs de cette alternance était de pouvoir en paralèlle de ma formation, pouvoir mettre en pratique et perfectionner les compétences acquises dans le cadre de ma formation _( PHP, Symfony, conception, versionning, etc...)_ .

<div class="divider"></div>

### **Organisation**

L'immersion en milieu professionnel m'a permise également de me familiariser avec les méthodes et l'**organisation du travail** au sein d'une agence web, comme par exemple :
- la **répartition des tâches** en fonction des priorités et d'une **estimation de temps** 
- l'organisation d'une **mise en production** d'une application web.

<div style="page-break-after: always;"></div>


<div align="center">

# Problématiques
</div>

<img src="img/prob-logo.png" class="sub-chap-img"><br>
Au cours de cette alternance j'ai été amené à devoir apporter une solution à plusieurs problématiques. 
Parmis celles-ci, les deux principales ont été :

<div class="divider"></div>

## **Comment intégrer une nouvelle fonctionnalité à une application existante ?**

Le développement de modules pour le CMS **Prestashop** composait la majeure partie de mes missions.<br> 
Il était donc nécessaire à pour chaque mission, de concevoir une solution qui permettrait d'intégrer une ou plusieurs nouvelles fonctionnalités, tout en veillant à ne pas perturber le **fonctionnement**  ou la **maintenabilité** de l'application.

Il est donc nécessaire d'avoir une bonne **connaissance de la structure de l'application** afin d'orienter son développement de manière à respecter l'architecture de celle-ci pour l'implémentation de nouvelles fonctionnalités.

<div class="divider"></div>

## **Comment configurer efficacement un environement de développement ?**

Dans le cadre de mon alternance j'ai été amené à travailler sur des applications web déjà existantes et utilisant des technologies plus ou moins anciennes. 

Il était donc nécessaire à chaque fois, de pouvoir reproduire un **environement de développement** local le plus fidèle possible à l'**environement de production** (version PHP, MySql, Composer, NodeJs, etc...). 

<div style="page-break-after: always;"></div>

<div align="center">

# Missions
</div>
<img src="img/organisation-du-travail.jpg" class="sub-chap-img"><br>

## Organisation du travail
<div class="divider"></div>

### **Attribution des tâches à effectuer**
Comme dans beaucoup d'agences, les tâches sont réparties sous formes de **tickets** qui sont attribués à un ou plusieurs développeurs.

Pour la gestion de ces **tickets**, nous utilisons l'outil `Wrike`. Le développeur peut avec cet outil consulter la liste des tickets qui lui ont été attribués, ajouter des observations, renseigner la durée de développement, indiquer un status, etc...

<div class="img-container">
   <img src="img/wrike_tasks_list.png" alt="wrike_tasks_lists">
</div>

<div style="page-break-after: always;"></div>

<!-- <img src="img/ticket.png" class="sub-chap-img"><br> -->

### **Détail d'un ticket**
Chacun de ces **tickets** contient un certain nombre d'informations sur le travail à effectuer :
- _Titre_
- _Client/Projet_
- _Description_
- _Dates de début et de fin estimée_
- _Estimation du temps nécessaire_
- _Personnes à qui ce ticket a été attribué_
- _etc..._

<div class="img-container">
   <img src="img/wrike_task_show.png" alt="wrike_task_show">
</div>

<div style="page-break-after: always;"></div>

<img src="img/tool-box.jpg" class="sub-chap-img"><br>

## Différentes technologies
<div class="divider"></div>
On peut distinguer les tâches qui m'ont été confiés par les technologies utilisées.

- La création/upgrade de modules __`Prestashop`__
- Développement de __`Scripts PHP`__ _(architecture fonctionnelle)_
- Développement d'applications __`Symfony/Sylius`__
- Création/upgrade de modules __`Wordpress`__

<div class="img-container">
   <img src="img/tasks-pie-chart.png" alt="répartissiion des technologies">
</div>

<div style="page-break-after: always;"></div>

<img src="img/task.png" class="sub-chap-img"><br>

## Présentation d'une mission
<div class="divider"></div>

L'une des plus importantes missions sur laquelle j'ai pu travailler est la conception d'un module de **marketplace** pour Prestashop.

### **Description**

Comme son nom l'indique ce module a pour rôle de créer une place de marché sur laquelle les utilisateurs peuvent proposer leurs propres produits.

Le module se décompose en 3 parties principales :
- Un menu de configuration du module dans le Back-Office natif du CMS permettant l'extension de certains composant de Prestashop. 
- Un espace d'administration destiné aux vendeurs ( _CRM_ ).
   Gestion des produits, transporteurs, promos, etc...
- Des fonctionnalités supplémentaires destinées à l'interactions entre les clients et les vendeurs ( _messagerie, avis, etc..._ ).

<div style="page-break-after: always;"></div>

### **Gestion de projet**
<div class="divider"></div>
A partir du cahier des charges le projet a été découpé en plusieurs tickets. 

Pour la plupart, ces tickets correspondaient aux différentes sections des menus de configuration ou à une fonctionnalité spécifique _( ex: page de gestion des transporteurs, affichage du nom du fournisseur sur la page produit )_.

<div class="img-container">
<img src="img/gestion_projet.png" alt="gestion_projet">
</div>
<div class="divider"></div>

Une fois le développement de la branche terminée, elle est fusionnée à la branche principale après avoir été validée par le responsable du projet _(review de code et tests manuels)_.
<div class="img-container">
<img src="img/gestion_projet_pr.png" alt="gestion_projet_pr">
</div>

<div style="page-break-after: always;"></div>

### **Fonctionnalités développées**
<div class="divider"></div>
Au cours des 9 mois de développement de ce module, les fonctionnalités sur lesquelles j'ai été amené à travailler m'ont permise d'acquérir ou de perfectionner un certain nombre de compétences :

| Contexte                                  | Compétence                                                                                                                             |
| ----------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------- |
| Développement d'un module                 | **Analyse** du fonctionnement d’une application/structure existante                                                                    |
| Profil fournisseur                        | Génération dynamique de fichier **PDF**                                                                                                |
| Tableau de bord                           | Génération de **graphiques** à partir de statistiques de vente                                                                         |
| Messages personnalisés                    | Traitement de données HTML fournis par le revendeur _(**TinyMCE**)_                                                                    |
| Import de produits                        | Traitement/Import/Export de fichiers sous différents formats:  **JSON**, **CSV**, **XML**, **image** en PHP                            |
| Pré-inscription                           | Pré-inscription d'un utilisateur; process de validation par token                                                                      |
| Messagerie                                | Système de messagerie : **interfaces** fournisseur & client , affichage par conversation, pagination, gestion de pièces jointes etc... |
| Gestion des rôles utilisateur             | Traitement de formulaire en **AJAX**                                                                                                   |
| Navigation à facettes (page fournisseurs) | Filtres configurables, chargement du contenu asyncrone                                                                                 |
| Souscription                              | Script php : vérification de la validité de l'abonnement _(**cron task**)_                                                             |

<div style="page-break-after: always;"></div>


<div align="center">

# Bilan
</div>
<img src="img/bilan.jpg" class="sub-chap-img"><br>

A l'issue de mon parcours de formation, il peut être intéressant de faire une analyse des différentes compétences que j'ai pu acquérir ou perfectionner durant cette période.

<div class="divider"></div>

## **Ce que j'ai appris dans le cadre de mon travail**

### **Savoir comprendre le fonctionnement d’une application/structure existante**
Travailler sur des projet comportant de **nombreuses contraintes technique**s m'a permis d'apprendre a **adapter** la conception d'une solution **aux besoins** du client mais également à ces contraintes.<br>
J'ai donc pu grandement améliorer ma capacité à :
- **Comprendre** et **analyse** le fonctionnement d'une structure
- S'**adapter** à des contraintes techniques
- Traduire les besoins/demandes d'un client en fonctionnalités
- Adapter le développement en fonction des différents besoins et contraintes

### **Compétences techniques**
Ce contexte m'a également permit de me perfectionner d'un point de vu technique. J'ai pu ainsi me familiariser avec :
- L'utilisation de requêtes **AJAX** _( front & back)_
- Manipulation de données sous différents **formats** _( xml, csv, json, images)_
- L'interaction avec des **services externes** _( API, CRM, etc... )_

<div style="page-break-after: always;"></div>

## **Ce que j'ai mis en pratique**
J'ai également pu mettre en pratique un grand nombre de connaissances acquise dans le cadre du programme de formation.

- **Conceptualiser** une application complète en décrivant sa structure
- Rédiger les spécifications détaillées d'un projet
- Respecter les **bonnes pratiques** de développement en vigueur
- Développement/consomation **API**
- Mettre en place des **tests unitaires et fonctionnels**
- Gérer le **versionning** d'un projet _( git )_

<div class="divider"></div>

## **Ce que j'ai apporté**

L'une des problématiques rencontrée au cours de cette période à été de pouvoir `configurer efficacement un environement de développement`.
En effet, comme abordé plus tôt, j'ai été amené à travailler sur des applications **plus ou moins anciennes** utilisant une configurations particulières _( version/modules php, dépendances, etc... )_.<br> 
Il était donc nécessaire de pouvoir **reproduire** de manière fidèle l'**environement** de production.<br>
Au cours de mon parcours de formation mon mentor m'a recommandé de m'initier à l'utilisation de `Docker`. Ce qui m'a permis de beaucoup simplement répondre a cette **problématique**.<br>
En accords avec le reste de l'équipe nous avons donc décider d'adopter cette solution pour un maximum de projet. <br>
Ce qui nous permet aujourd'hui de pouvoir travailler sur des environement identiques aussi bien pour le développement que pour la production.

<div style="page-break-after: always;"></div>

## **Conclusion**

En conclusion, je dirais que mon expérience au sien d'une agence ayant plus de 14 ans d'existance m'a permis de mieux comprendre l'évolution des technologies utilisées dans le domaine du développement web et ainsi être plus à l'aise avec leurs utilisations.<br>
Il m'est aujourd'hui plus simple de comprendre le fonctionnement et l'utilisation des outils existant, qu'il soit récent ou plus anciens.

<div class="divider"></div>

## **Après l'alternance**
A l'issue de ma période d'alternance, mon employeur m'a proposé un emploi au sein de l'entreprise. Greentic a pour projet de s'orienter de plus en plus vers l'utilisation de solution comme `Symfony` et `Sylius` pour les projets e-commerce. Je vais donc pouvoir me perfectionner d'avantage en tant que développeur sur ces technologies. 