# 💼 Assetium — Gestionnaire de Parc Informatique

**Assetium** est une solution logicielle fullstack de gestion d'actifs IT (matériel, logiciels, utilisateurs, tickets) basée sur une architecture moderne **Vue.js + Node.js + Express + MySQL**,[...]

---

## 🧱 Stack Technologique

| Couche | Technologie |
|--------|-------------|
| Frontend | Vue.js 3 (Composition API, Vue Router, Pinia, Tailwind CSS) |
| Backend | Node.js 22 + Express.js |
| Base de données | MySQL 8 |
| Authentification | JWT, Bcrypt |
| Sécurité | CORS, RBAC, validation & sanitation |

---

## 📦 Modules Fonctionnels

### 📁 Inventaire
- Matériels : PC, serveurs, imprimantes, périphériques
- Statut et historique des affectations
- Alertes sur fin de garantie ou disponibilité

### 👥 Utilisateurs & Rôles
- Connexion sécurisée via JWT
- Gestion des profils et des rôles (Admin, Tech, Standard)
- Journalisation des actions critiques

### 🛠️ Maintenance & Tickets
- Ouverture de ticket par utilisateur
- Affectation automatique ou manuelle à un technicien
- Suivi des statuts & historique d'intervention

### 📊 Dashboard (Admin & Technicien)
- KPIs matériels, utilisateurs, tickets
- Graphiques dynamiques (ECharts)
- Filtres et recherche multi-critères

---

## 🔐 Sécurité

- Authentification par **JWT**
- Chiffrement des mots de passe avec **Bcrypt**
- Middleware de vérification d'accès selon le rôle
- Validation des entrées utilisateur et prévention XSS/SQLi

---

## 🧪 Stack Dev & Démarrage

### 📁 Backend


- cd backend
- cp .env.example .env
- Configurer :
    - DB_HOST
    - DATABASE_PORT
    - SERVER_PORT
    - DB_USER
    - DB_PASS
    - DB_NAME
    - JWT_SECRET

#### npm install
#### npm run dev

## Demo

#### Dashboard
<img src="demos/dashboard.png" />

#### Equipements
<img src="demos/equipements.png" />

