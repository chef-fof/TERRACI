# 🏡 TerraCI - Plateforme Immobilière Moderne

Plateforme moderne et sécurisée pour l'achat et la vente de terrains en Côte d'Ivoire.

## 🎯 Fonctionnalités

- ✅ Publication et gestion de terrains
- ✅ Recherche avancée avec filtres
- ✅ Carte interactive (Leaflet)
- ✅ Messagerie temps réel (Socket.IO)
- ✅ Système d'offres sécurisé
- ✅ Dashboard utilisateur
- ✅ Panel administrateur
- ✅ Authentification JWT

## 📋 Stack Technique

**Frontend**: React 18 + Vite + Tailwind CSS + Framer Motion
**Backend**: Node.js + Express + PostgreSQL + Socket.IO
**Sécurité**: JWT + Bcrypt + Helmet

## 🚀 Installation

### Frontend
```bash
cd frontend
npm install
npm run dev
```

### Backend
```bash
cd backend
npm install
cp .env.example .env
npm run dev
```

### Base de données
```bash
psql -U postgres -c "CREATE DATABASE terraci;"
psql -U postgres -d terraci -f database/schema.sql
```

## 🎨 Design
- Couleur principale: #163B34 (vert foncé)
- Accent: #CFA761 (or)
- Inspiré par Airbnb, Zillow, Booking.com

## 📖 Documentation API
Les routes API sont disponibles dans `backend/routes/`

---

**Prêt pour production** 🚀
