# 🚁 Drone Battery Tracker - PWA

Application Web Progressive (PWA) professionnelle pour le suivi des cycles de batteries de drone.

## ✨ Fonctionnalités

- ✅ Ajout/suppression de batteries numérotées
- ✅ Enregistrement de chaque vol (temps, voltage min/cell)
- ✅ Système de signalement de problèmes
- ✅ Compteur de cycles automatique
- ✅ Historique détaillé par batterie
- ✅ **Fonctionne hors ligne** (PWA)
- ✅ **Installable sur téléphone/tablette/PC**
- ✅ Sauvegarde locale automatique
- ✅ Design moderne et responsive

## 📱 Installation

### Sur Android/iOS :

1. Ouvrez le fichier `index.html` dans votre navigateur (Chrome, Safari, Firefox)
2. Cliquez sur "Installer" dans le prompt qui apparaît
   - **Ou** utilisez le menu du navigateur → "Ajouter à l'écran d'accueil"
3. L'icône de l'app apparaît sur votre écran d'accueil
4. Lancez l'app comme n'importe quelle application native !

### Sur PC (Windows/Mac/Linux) :

1. Ouvrez le fichier `index.html` dans Chrome ou Edge
2. Cliquez sur l'icône d'installation dans la barre d'adresse (➕)
3. Confirmez l'installation
4. L'app s'ouvre dans sa propre fenêtre, comme une app native !

## 🌐 Hébergement (optionnel)

Pour accéder à votre app depuis n'importe où via une URL :

### Option 1 : GitHub Pages (GRATUIT)
1. Créez un compte GitHub
2. Créez un nouveau repository
3. Uploadez les 4 fichiers (index.html, manifest.json, sw.js, README.md)
4. Dans Settings → Pages → activez GitHub Pages
5. Votre app sera accessible à : `https://votre-username.github.io/nom-repo`

### Option 2 : Netlify (GRATUIT)
1. Allez sur netlify.com
2. Drag & drop le dossier complet
3. Votre app est en ligne en 30 secondes !
4. URL fournie automatiquement

### Option 3 : Vercel (GRATUIT)
1. Allez sur vercel.com
2. Importez le projet
3. Déployé automatiquement !

## 💾 Stockage des Données

- **Local** : Toutes les données sont sauvegardées dans le navigateur (localStorage)
- **Persistance** : Les données restent même après fermeture
- **Hors ligne** : L'app fonctionne sans connexion internet
- **Export** : Vous pouvez exporter vos données manuellement si besoin

## 🔮 Évolution Future : Synchronisation Cloud

Pour synchroniser entre plusieurs appareils, vous pourrez plus tard :
- Connecter à Supabase (base de données gratuite)
- Ajouter un système de compte utilisateur
- Synchronisation automatique entre téléphone/tablette/PC

## 🛠️ Structure des Fichiers

```
drone-battery-pwa/
├── index.html          # Application principale
├── manifest.json       # Configuration PWA
├── sw.js              # Service Worker (fonctionnement hors ligne)
└── README.md          # Ce fichier
```

## 📊 Utilisation

1. **Ajouter une batterie** : Entrez un numéro et cliquez sur "Ajouter"
2. **Logger un vol** : 
   - Sélectionnez la batterie
   - Entrez le temps de vol et voltage minimum
   - Cochez "Problème" si nécessaire
   - Enregistrez
3. **Consulter l'historique** : Sélectionnez une batterie dans le menu déroulant

## 🎨 Design

- Interface moderne avec animations fluides
- Thème sombre optimisé pour usage extérieur
- Police monospace pour les données techniques
- Responsive : s'adapte à tous les écrans

## 🔒 Sécurité & Confidentialité

- Aucune donnée envoyée en ligne (100% local)
- Pas de tracking
- Pas de compte requis
- Vos données restent sur votre appareil

## 💡 Conseils

- Installez l'app pour un accès rapide
- Utilisez-la avant et après chaque vol
- Notez les problèmes immédiatement pour ne rien oublier
- Consultez régulièrement les cycles pour planifier les remplacements

## 🚀 Technologies

- HTML5 + CSS3 + Vanilla JavaScript
- Progressive Web App (PWA)
- Service Worker pour mode hors ligne
- LocalStorage pour la persistance
- Design responsive moderne

---

**Créé pour les pilotes de drone qui veulent suivre leurs équipements professionnellement** 🚁⚡
