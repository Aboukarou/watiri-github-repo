
# 🚗 Watiri – Plateforme d'achat, vente et location de voitures

Watiri est une Web App complète avec :
- 🔥 Frontend en React (Vite)
- 🛠️ Backend Node.js + Express + MongoDB
- 💸 Commission automatique pour l’admin
- 📱 Design responsive sans Tailwind

## 🔧 Stack
- React + Vite
- Express + Node.js
- MongoDB (Atlas)
- Déploiement : Vercel (frontend) + Railway (backend)

---

## 📁 Structure du repo

```
watiri/
├── client/     # Frontend React (Vite)
├── server/     # Backend Node.js + Express + MongoDB
```

---

## 🚀 Déploiement

### Frontend sur Vercel
1. [Créer un compte Vercel](https://vercel.com)
2. Uploader le dossier `client/`
3. Build command: `vite build`
4. Output directory: `dist`
5. Ajoute le fichier `vercel.json` pour la redirection vers l'API

### Backend sur Railway
1. [Créer un compte Railway](https://railway.app)
2. Nouveau projet → Upload `server/`
3. Ajoute `.env` → `MONGO_URI=your_mongo_connection_string`

### MongoDB Atlas
- [Créer un cluster gratuit ici](https://www.mongodb.com/cloud/atlas)

---

## ✅ Pour lancer localement

### Backend
```bash
cd server
npm install
node server.js
```

### Frontend
```bash
cd client
npm install
npm run dev
```

---

> Made with ❤️ by ChatGPT for Watiri Project
