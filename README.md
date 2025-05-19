# BlackjackGame 🎲

## 📝 Présentation
**BlackjackGame** est une application **desktop** moderne permettant aux utilisateurs de jouer au célèbre **jeu de Blackjack** avec une interface graphique intuitive et des fonctionnalités avancées.

Développée avec **Electron, React.js et TypeScript**, elle offre une **expérience fluide et agréable**, avec un design moderne grâce à **TailwindCSS** et des animations fluides avec **Framer Motion**.

---

## 🚀 Fonctionnalités
✅ **Gestion du jeu**  
- Distribution automatique des cartes  
- Actions du joueur : **Tirer, Rester, Doubler**  
- Calcul des scores en temps réel  
- Détection des **Blackjacks**  
- Gestion du **tour du croupier**  

✅ **Système de mise**  
- Interface intuitive pour placer des mises  
- Gestion du **solde du joueur**  
- Calcul automatique des **gains et pertes**  
- Paiement **3:2 pour Blackjack**  

✅ **Interface utilisateur moderne**  
- Affichage des cartes avec **animations fluides**  
- Messages en temps réel pour informer l’utilisateur  
- Menu de **règles** accessible à tout moment  
- Design **responsive** pour une expérience optimale  

---

## 🛠 Technologies utilisées
🖥 **Développement Desktop**  
- [Electron](https://www.electronjs.org/) – Création d’application multiplateforme  
- [React.js](https://react.dev/) – Interface utilisateur dynamique  
- [TypeScript](https://www.typescriptlang.org/) – Typage statique pour une meilleure maintenabilité  

🎨 **UI / Animations**  
- [TailwindCSS](https://tailwindcss.com/) – Framework CSS moderne et rapide  
- [Framer Motion](https://www.framer.com/motion/) – Animations fluides  

🔗 **Gestion du projet**  
- **Node.js** – Environnement d’exécution  
- **npm** – Gestionnaire de paquets  
- **Electron Builder** – Packaging et création d’installateurs  

---

## 📂 Structure du projet  
```plaintext
blackjack-game/
├── src/
│   ├── components/
│   │   ├── Game.tsx
│   │   ├── Card.tsx
│   │   ├── BettingControls.tsx
│   │   └── GameControls.tsx
│   ├── hooks/
│   │   └── useGameLogic.ts
│   ├── types/
│   │   └── game.ts
│   └── App.tsx
├── electron/
│   ├── main.js
│   └── preload.js
└── public/
