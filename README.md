# 🏨 Hotel Website

Site web d’hôtel développé en **PHP / MySQL**, permettant la présentation de l’établissement, la consultation des chambres, la réservation en ligne et la gestion des comptes utilisateurs.

## 🌐 Démo en ligne

👉 [Voir le site](https://lightsalmon-nightingale-878312.hostingersite.com)

---

## 📌 Description

Ce projet est un site web d’hôtel conçu pour offrir une expérience simple et intuitive aux visiteurs.

Il permet notamment de :

- présenter l’hôtel et ses services
- consulter les chambres disponibles
- réserver une chambre
- contacter l’hôtel via un formulaire
- créer un compte utilisateur
- se connecter à son espace

---

## ✨ Fonctionnalités

### Côté visiteur
- Page d’accueil de présentation
- Consultation des chambres
- Consultation des services proposés
- Formulaire de contact
- Création de compte
- Connexion utilisateur

### Côté utilisateur connecté
- Réservation de chambre
- Accès à un espace personnel selon le rôle

### Côté administration
- Gestion des chambres
- Gestion des utilisateurs
- Gestion des réservations

---

## 🛠️ Technologies utilisées

- **PHP** — logique back-end
- **MySQL** — base de données
- **HTML / CSS** — structure et mise en page
- **JavaScript** — interactions côté client
- **EmailJS** — envoi d’e-mails via le formulaire de contact
- **Composer** — gestion des dépendances PHP
- **phpdotenv** — gestion des variables d’environnement

---

## 🗂️ Structure du projet

```bash
public/
│── index.php
│── reservation.php
│── assets/
│   ├── css/
│   ├── js/
│   └── images/

src/
│── config/
│   └── Database.php
│── controllers/
│── models/
│   ├── User.php
│   ├── Room.php
│   └── Reservation.php
│── views/
│   ├── auth/
│   ├── partials/
│   └── ...
