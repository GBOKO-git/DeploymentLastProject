

# 🎓 AEEY — Plateforme de Gestion Associative Étudiante

**AEEY** est une plateforme web dédiée aux associations étudiantes pour gérer facilement leurs membres, événements, dons et cotisations.

🌐 Voir le site: https://aeey.netlify.app/ · 
🔐 API en ligne: https://last-project-server-1.onrender.com

---

## ✨ Fonctionnalités

- Authentification sécurisée (JWT)
- Rôles utilisateur (admin, membre, donateur, invité)
- Validation d’adhésion par l’administrateur
- Tableau de bord administrateur
## - Système de dons et cotisation avec intégration PayPal, strype et cinetpay en cours de production
- Création/gestion d’événements
## - Upload d’image de profil et événements (Cloudinary) en cours de production

---

## 🧱 Technologies utilisées

### Frontend (React + Vite)
- Vite, React Router DOM
- Tailwind CSS
- Axios, React Toastify
- PayPal React SDK
- cinetpay
-strype

### Backend (Express + MongoDB)
- Express.js 5, Mongoose 8
- JWT, BcryptJS
- Multer (upload fichiers)
- Cloudinary (images)
- Nodemailer (emails)
- PayPal Checkout Server SDK

---

## 📦 Installation locale

### Backend


git clone https://github.com/GBOKO-git/DeploymentLastProject.git
cd last_project
npm install
cp .env.example .env
npm run dev



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
