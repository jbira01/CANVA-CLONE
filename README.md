<div align="center">

# 🎨 Canva Clone – Online Graphic Design Platform

### Plateforme d’Édition Graphique en Ligne (Architecture Microservices)

![Next.js](https://img.shields.io/badge/Next.js-14+-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-18+-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-18+-339933?style=for-the-badge&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-Database-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Fabric.js](https://img.shields.io/badge/Fabric.js-Canvas-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-In_Development-blue?style=for-the-badge)

Projet académique – Plateforme complète inspirée de Canva

</div>

---

## 📖 Présentation

Cette application est une **plateforme d’édition graphique en ligne** inspirée de Canva.  
Elle permet aux utilisateurs de créer, modifier, sauvegarder et exporter des designs professionnels directement depuis leur navigateur.

Le projet est construit avec une **architecture microservices scalable** et des technologies modernes (Next.js, Fabric.js, Node.js, MongoDB).

---

## 🎯 Objectifs

- Offrir une alternative moderne aux outils de design en ligne
- Fournir une expérience utilisateur fluide et intuitive
- Implémenter une architecture microservices maintenable
- Intégrer un modèle économique freemium

---

## 🏗️ Architecture Technique

### 🔹 Frontend
- Next.js 14+ (React)
- Fabric.js (manipulation du canvas HTML5)
- Zustand (state management)
- TailwindCSS + Shadcn UI
- Auth.js (NextAuth v5)

### 🔹 Backend (Microservices)
- Node.js + Express
- API Gateway
- MongoDB (base de données)
- Cloudinary (stockage d’images)
- PayPal API (abonnements)

---

## 🧩 Architecture Microservices

L’application est organisée autour d’un **API Gateway** qui redirige les requêtes vers :

### 1️⃣ Upload Service
- Téléchargement d’images
- Intégration Cloudinary
- Optimisation et stockage sécurisé

### 2️⃣ Design Service
- Création et gestion des projets
- Sauvegarde automatique
- Historique des versions
- Export multi-format (PNG, JPG, SVG, JSON)

### 3️⃣ Subscription Service
- Gestion des abonnements
- Intégration PayPal
- Gestion des paiements
- Contrôle des fonctionnalités premium

---

## ✨ Fonctionnalités

### 🎨 Éditeur Canvas
- Ajout de formes (rectangle, cercle, triangle, polygones)
- Insertion et édition de texte
- Import d’images
- Rotation, redimensionnement, positionnement
- Gestion des calques (Z-index)
- Groupement / dégroupement
- Dessin à main levée

### 🤖 Génération d’Images par IA
- Saisie de prompts
- Prévisualisation
- Insertion directe dans le canvas
- Fonctionnalité Premium

### 💾 Gestion des Designs
- Sauvegarde automatique
- Chargement de projets
- Suppression
- Export multi-format

### 💳 Système Freemium

#### Compte Gratuit
- Maximum 5 projets
- IA désactivée
- Export disponible

#### Compte Premium
- Projets illimités
- Génération IA activée
- Stockage étendu
- Support prioritaire

---

## 🔐 Sécurité

- Authentification sécurisée via Auth.js
- Protection CSRF
- Gestion des tokens via middleware
- Sessions sécurisées
- Contrôle d’accès basé sur abonnement

---

## ⚡ Performance

- Server-Side Rendering (SSR) avec Next.js
- Lazy loading des composants
- Optimisation Cloudinary
- Debouncing pour la sauvegarde automatique
- Cache stratégique

---

## 📱 Responsive Design

- Interface adaptée Desktop / Tablet / Mobile
- UI moderne avec TailwindCSS
- Composants réactifs Shadcn

---

## 🚀 Installation (Développement)

### 1️⃣ Cloner le projet

```bash
git clone https://github.com/your-username/canva-clone.git
cd canva-clone
```

### 2️⃣ Installer les dépendances

Frontend :

```bash
npm install
```

Backend (dans chaque microservice) :

```bash
npm install
```

### 3️⃣ Configuration

Créer un fichier `.env` :

```env
MONGODB_URI=
CLOUDINARY_API_KEY=
CLOUDINARY_SECRET=
PAYPAL_CLIENT_ID=
PAYPAL_SECRET=
NEXTAUTH_SECRET=
```

### 4️⃣ Lancer le projet

Frontend :

```bash
npm run dev
```

Backend :

```bash
npm run dev
```

---

## 📈 Roadmap

- Ajout de templates prédéfinis
- Collaboration en temps réel
- Mode offline
- Déploiement Docker
- Monitoring production

---

## 👨‍💻 Auteur

Yasser Jabir  
Développeur Full Stack  

---

## 📄 Licence

Projet académique – Usage éducatif
