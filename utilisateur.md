# 👤 Documentation Utilisateur — Parcours & Fonctionnalités

Ce document détaille l'expérience utilisateur au sein de la plateforme et la logique des parcours proposés aux étudiants.

---

## 🧭 Parcours Utilisateur Global

```mermaid
sequenceDiagram
    participant Etudiant as Étudiant (Visiteur)
    participant Site as Guide de Survie (index1.html)
    participant Local as Stockage Navigateur (localStorage)

    Etudiant->>Site: Arrivée sur le site
    Site->>Etudiant: Affichage de la modale d'authentification / profil
    Etudiant-->>Local: Saisie des informations (Nom, Prénom, Identifiant)
    Local-->>Site: Sauvegarde et chargement du profil
    Site->>Etudiant: Déblocage complet du guide et des outils interactifs
    Etudiant->>Site: Utilisation de la To-Do List & Simulateur de Budget
    Site-->>Local: Mise à jour automatique des données personnelles
