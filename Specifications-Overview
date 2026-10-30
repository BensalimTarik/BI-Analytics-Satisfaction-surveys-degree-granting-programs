# Projet BI – Analyse de la satisfaction des étudiants

## 1. Présentation du projet

Ce projet consiste à concevoir et mettre en place un dispositif de collecte, de traitement et d’analyse des enquêtes de satisfaction des étudiants du groupe **Compétences & Développement (C&D)**.

La solution permet de suivre et d’analyser la satisfaction des étudiants sur plusieurs dimensions : qualité de l’enseignement, accompagnement, information et orientation, organisation logistique et valeur perçue de la formation.

L’objectif est de centraliser les données, d’automatiser les traitements et de mettre à disposition des responsables pédagogiques et des directions des tableaux de bord interactifs sous Power BI.

## 2. Objectifs métier

Le projet répond à six objectifs principaux :

- **O1 – Création des questionnaires :** concevoir des questionnaires adaptés aux différents axes d’évaluation.
- **O2 – Automatisation des envois :** automatiser la diffusion des questionnaires auprès des étudiants concernés.
- **O3 – Centralisation des réponses :** automatiser la collecte et le stockage des réponses.
- **O4 – Préparation des données :** nettoyer, transformer et structurer les données pour garantir leur exploitabilité.
- **O5 – Pilotage par les indicateurs :** mettre à disposition des tableaux de bord interactifs présentant les indicateurs prioritaires.
- **O6 – Aide à la décision :** permettre aux responsables pédagogiques et métiers d'identifier les tendances, les points forts et les axes d'amélioration.

## 3. Périmètre fonctionnel et processus métier

La solution repose sur quatre grandes étapes.

### Étape 1 – Extraction et préparation des données

- Extraction des données depuis le système IGOR.
- Transfert et stockage dans une base de données SQL Server dédiée.
- Application de contrôles de qualité et de règles de transformation.
- Réduction des traitements manuels sous Excel.
- Standardisation et traçabilité des actualisations.

### Étape 2 – Création et diffusion des questionnaires

- Création de formulaires HTML adaptés à l'identité visuelle de chaque école.
- Attribution d'un identifiant unique permettant de rattacher chaque réponse à une enquête et à une période de formation.
- Automatisation de la sélection des destinataires et de l'envoi des questionnaires.
- Amélioration du suivi des invitations et réduction des erreurs de diffusion.

### Étape 3 – Collecte et centralisation des réponses

- Automatisation du traitement des réponses avec Azure Logic Apps.
- Enregistrement des réponses dans une base de données dédiée.
- Contrôle de la validité des réponses.
- Prévention des doublons.
- Suivi des erreurs de traitement.

### Étape 4 – Analyse et restitution sous Power BI

- Conception de rapports interactifs sous Power BI.
- Organisation des rapports en plusieurs pages thématiques.
- Mise en place d'un modèle de données en étoile, structuré autour de tables de faits et de dimensions.
- Analyse de la satisfaction par école, formation, promotion et axe d'évaluation.
- Actualisation et maintenance des tableaux de bord.

## 4. Indicateurs clés de performance (KPI)

Les tableaux de bord permettent notamment de suivre les indicateurs suivants :

| Indicateur | Définition |
|---|---|
| Nombre de réponses | Nombre de réponses valides après déduplication |
| Taux de réponse | Nombre de répondants / nombre d'étudiants invités × 100 |
| Nombre de notifications envoyées | Nombre d'invitations et de relances envoyées |
| Taux de conversion des invitations | Nombre de répondants / nombre d'invités × 100 |
| CSAT | Part des notes 4 et 5 sur une échelle de 1 à 5 |
| Satisfaction moyenne | Moyenne des notes de satisfaction valides |
| NPS | Pourcentage de promoteurs (9-10) moins pourcentage de détracteurs (0-6) |
| Satisfaction par dimension | Part des réponses satisfaites pour chaque axe d'analyse |
| Taux de commentaires exploitables | Nombre de commentaires renseignés / nombre de répondants concernés × 100 |

**Objectifs indicatifs mentionnés dans les spécifications :**
- Taux de réponse : ≥ 70 %.
- Notifications planifiées : 100 % traitées.
- Les autres objectifs sont à définir ou à confirmer selon les indicateurs et les premières campagnes.

## 5. Architecture des données et sources

### Sources de données

**Source 1 – IGOR / SQL Server**

Données relatives notamment :
- Aux inscriptions et aux étudiants.
- Aux formations.
- Aux axes d'analyse.
- À l'année scolaire en cours.

L'accès aux données est effectué en lecture seule, selon les autorisations accordées.

**Source 2 – Base SQL Server dédiée Data Analytics**

Cette base contient les données structurées et préparées pour les traitements et les analyses.

Les opérations de lecture et d'écriture sont contrôlées selon les besoins du processus.

### Technologies utilisées

- **IGOR :** système source des données.
- **SQL Server :** stockage et centralisation des données.
- **Azure Logic Apps :** automatisation des traitements et de la collecte des réponses.
- **HTML :** conception des questionnaires.
- **Power BI :** modélisation, analyse et visualisation des données.

## 6. Règles de gestion et qualité des données

Le dispositif intègre plusieurs contrôles afin de fiabiliser les résultats :

- Vérification de la validité des réponses.
- Identification et prévention des doublons.
- Contrôle de la cohérence des données collectées.
- Centralisation des réponses dans une base dédiée.
- Préparation et nettoyage des données avant leur exploitation.
- Traçabilité des traitements et des actualisations.

## 7. Valeur ajoutée du projet

La solution apporte plusieurs bénéfices opérationnels et décisionnels :

- Automatisation d'une partie importante du processus de collecte et de traitement.
- Réduction des manipulations manuelles et des risques d'erreur.
- Centralisation et fiabilisation des données.
- Amélioration de la visibilité sur la satisfaction des étudiants.
- Suivi des indicateurs par école, formation, promotion et dimension d'analyse.
- Identification des points forts et des axes d'amélioration.
- Mise à disposition d'un outil d'aide à la décision pour les équipes pédagogiques et les directions.

---

*Projet réalisé dans le cadre de l'analyse de la satisfaction des étudiants du groupe Compétences & Développement.*
