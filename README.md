# InvestLink

InvestLink is a platform that bridges the gap between **entrepreneurs** with innovative ideas and **investors** looking for promising opportunities. It provides a secure and interactive environment for networking, collaboration, and funding.

## 📑 Table of Contents

1. [Aperçu du projet](#aperçu-du-projet)
2. [Problématique](#problématique)
3. [Solution proposée](#solution-proposée)
4. [Fonctionnalités](#fonctionnalités)
5. [Cas d'utilisation](#cas-dutilisation)
6. [Technologies utilisées](#technologies-utilisées)
7. [Architecture du projet](#architecture-du-projet)
8. [Installation](#installation)

---

## 🏆 Aperçu du projet

InvestLink est une plateforme innovante permettant de connecter les entrepreneurs et les investisseurs en toute sécurité. Elle offre un espace collaboratif où les idées peuvent devenir des opportunités d’affaires concrètes.

---

## ❓ Problématique

Le manque de connexion entre entrepreneurs et investisseurs empêche de nombreuses idées innovantes de voir le jour. D’un côté, les entrepreneurs manquent de financement, et de l’autre, les investisseurs recherchent des projets prometteurs. **Comment faciliter cette mise en relation de manière efficace et sécurisée ?**

---

## 💡 Solution proposée

InvestLink propose une plateforme où :
- Les **entrepreneurs** peuvent publier leurs projets, détailler leurs idées et améliorer leur visibilité.
- Les **investisseurs** peuvent découvrir ces opportunités, entrer en contact avec les entrepreneurs et investir en toute sécurité.

Grâce à des **outils intelligents de matchmaking, de messagerie et d’analyse**, InvestLink fluidifie le processus d’investissement et optimise les opportunités de collaboration.

---

## 🚀 Fonctionnalités

- **Interface intuitive** pour publier et découvrir des projets.
- **Système de matching intelligent** basé sur les intérêts des utilisateurs.
- **Messagerie** pour faciliter les discussions.
- **Outils d’analyse et statistiques** pour une meilleure prise de décision.
- **Profils détaillés** des entrepreneurs et investisseurs.
- **Gestion des favoris** pour sauvegarder des projets intéressants.
- **Système de vérification des utilisateurs** pour garantir la fiabilité des échanges.
- **Recommandations basées sur l’IA** pour suggérer des projets aux investisseurs.
- **Exportation de données et rapports** pour un suivi des investissements.

---

## 📌 Cas d'utilisation

1. Un **entrepreneur** souhaite lever des fonds pour son projet innovant. Il s’inscrit, complète son profil et publie son projet.
2. Un **investisseur** cherche des opportunités, consulte les profils, explore les projets et entre en contact avec des entrepreneurs.
3. Un **Système de messagerie** facilite la mise en relation en fonction des intérêts et préférences des utilisateurs.
4. Une **discussion sécurisée** est engagée avant toute transaction ou prise de décision.

---

## 🏗️ Technologies utilisées

- **Frontend :** React Native Expo
- **Backend :** NestJS (Microservices Architecture)
- **Base de données :** MySQL & MongoDB
- **Authentification :** Keycloak
- **Stockage :** MinIO pour images et documents
- **Déploiement :** Docker
- **Messages :** Socket Io

---

## 🏛️ Architecture du projet

InvestLink repose sur une **architecture microservices** avec un **API Gateway** pour centraliser les requêtes.

- **Service Auth** : Gestion des utilisateurs et authentification via **Keycloak**.
- **Service Projets** : Publication et gestion des projets des entrepreneurs.
- **Service Messagerie** : Communication en temps réel entre entrepreneurs et investisseurs.
- **Service Posts** : Publication et gestion des **idées de projets** sous forme de posts visibles par les investisseurs.
- **Service Requests** : Gestion des **demandes de mise en relation** entre investisseurs et entrepreneurs.
- **Service AI** : Suggestion automatique des **tags et catégories** en fonction de la description du post, grâce à une **intelligence artificielle**.
- **Service Audit** : Suivi et journalisation des **actions et interactions** pour garantir la transparence et la sécurité de la plateforme.

---

## ⚙️ Installation

```sh
git clone https://github.com/walid-lhaila/INVEST-APP.git
cd INVEST-APP
npm install
