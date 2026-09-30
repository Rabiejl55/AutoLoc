# AutoLoc
Plateforme de gestion de location de véhicules multi-agences — UP ASI ESPRIT
# AutoLoc — Plateforme de gestion de location de véhicules multi-agences

**UP ASI — Architecture des Systèmes d'Information**
**Étude de cas : AutoLoc**
**Équipe :** Rabie Jlassi

---

## 🎯 Objectifs du projet

AutoLoc est une plateforme de gestion de location de véhicules
multi-agences permettant de gérer le parc de véhicules, les agences,
les clients, les réservations et la facturation.

L'objectif pédagogique est de concevoir et développer une application
Java / Spring Boot en respectant les bonnes pratiques d'architecture
(multi-couches, DTO, tests, etc.).

---

## 👥 Acteurs identifiés

| Acteur | Rôle principal |
|---|---|
| **Client** | Recherche un véhicule, effectue une réservation, consulte son historique |
| **Agent d'agence** | Enregistre les locations, gère les retours, édite les contrats |
| **Responsable d'agence** | Supervise l'agence, gère le parc, consulte les statistiques |
| **Administrateur** | Gère les utilisateurs, les agences, les droits, la configuration |

---

## 📋 Cas d'utilisation principaux

### Client
- Consulter le catalogue de véhicules disponibles
- Rechercher un véhicule selon des critères (agence, dates, type, prix)
- Effectuer une réservation
- Consulter / annuler ses réservations
- Consulter son historique

### Agent d'agence
- Enregistrer le départ d'un véhicule (check-out)
- Enregistrer le retour d'un véhicule (check-in)
- Générer un contrat de location
- Gérer les paiements et cautions

### Responsable d'agence
- Ajouter / modifier / retirer un véhicule du parc
- Suivre l'état du parc (disponible, loué, maintenance)
- Consulter les statistiques de l'agence
- Gérer les agents de son agence

### Administrateur
- Créer / gérer les agences
- Créer / gérer les comptes utilisateurs et rôles
- Configurer les paramètres globaux
- Consulter les statistiques globales

---

## 🧰 Stack technique

- **Langage** : Java 17+
- **Framework** : Spring Boot 3.x (Spring MVC, Spring Data JPA, Spring AOP)
- **Base de données** : MySQL 8.x (dev), H2 (tests)
- **Build** : Maven
- **Productivité** : Lombok, MapStruct (optionnel)
- **Documentation API** : springdoc-openapi (Swagger UI)
- **Tests** : JUnit 5, Mockito, MockMvc
- **Outils** : IntelliJ IDEA Ultimate, Postman, Git

---

## 🚀 Statut

- [x] Atelier 0 — Mise en place de l'environnement
- [ ] Atelier 1 — À venir