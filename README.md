# 💕 Pour Samuella - Saint Valentin 3D

Un site web 3D interactif créé avec Three.js pour offrir à Samuella comme cadeau de Saint Valentin.

## ✨ Fonctionnalités

- **Scène 3D romantique** avec un cœur central animé
- **5 poèmes d'amour interactifs** cachés dans des cœurs flottants
- **Effets visuels** : particules, lumières, animations fluides
- **100% Responsive** : optimisé pour mobile et desktop
- **Interactions tactiles** : toucher les cœurs sur téléphone pour révéler les poèmes

## 🚀 Déploiement sur Vercel

### Méthode 1 : Via le CLI Vercel (Recommandé)

1. **Installer Vercel CLI** (si pas déjà fait) :
   ```bash
   npm i -g vercel
   ```

2. **Se connecter à Vercel** :
   ```bash
   vercel login
   ```
   Suivre les instructions (vérification par email)

3. **Déployer le projet** :
   ```bash
   cd valentine-samuella
   vercel
   ```

   Répondre aux questions :
   - "Link to existing project?" → `N` (Non, nouveau projet)
   - "What's your project name?" → `pour-samuella` (ou le nom que tu veux)
   - "Which directory is your code located?" → `.` (point pour dossier actuel)

4. **Résultat** : Vercel te donne une URL instantanée ! 🎉

### Méthode 2 : Via GitHub + Vercel (Automatique)

1. **Créer un repo GitHub** :
   ```bash
   git init
   git add .
   git commit -m "Premier commit - Saint Valentin pour Samuella"
   git branch -M main
   git remote add origin https://github.com/TON_USERNAME/pour-samuella.git
   git push -u origin main
   ```

2. **Connecter à Vercel** :
   - Aller sur [vercel.com](https://vercel.com)
   - Cliquer "Add New Project"
   - Importer le repo GitHub
   - Framework Preset : "Other" (site statique)
   - Cliquer "Deploy"

3. **Avantage** : Chaque `git push` redéploie automatiquement !

### Méthode 3 : Drag & Drop (Plus simple)

1. Compresser le dossier `valentine-samuella` en ZIP
2. Aller sur [vercel.com](https://vercel.com)
3. Glisser-déposer le ZIP sur le dashboard
4. C'est déployé !

## 📱 Optimisations Mobile

Le site est déjà optimisé pour le téléphone de Samuella :
- Touch events pour interagir avec les cœurs
- Performance réduite sur mobile pour batterie fluide
- UI adaptée aux petits écrans
- Pas de zoom désactivé pour l'immersion

## 🎨 Personnalisation

Pour modifier les poèmes, éditer le fichier `main.js` :
```javascript
const poems = [
    {
        title: "Ton titre",
        text: `Ton poème ici...`,
        color: 0xff6b9d  // Couleur du cœur
    },
    // ...
];
```

## 🔧 Structure du Projet

```
valentine-samuella/
├── index.html          # Structure et styles
├── main.js             # Logique Three.js et poèmes
└── README.md           # Ce fichier
```

## 💝 Conseils pour Samuella

1. **Envoie-lui le lien** par message avec un 💌
2. **Dis-lui** : "Touche les cœurs roses flottants pour découvrir mes poèmes pour toi"
3. **C'est tout !** Le site guide l'utilisateur avec des instructions

## 🆘 Problèmes courants

**Le site ne s'affiche pas ?**
- Vérifier que `index.html` est à la racine
- Vérifier que les imports Three.js sont corrects

**Les poèmes ne s'ouvrent pas ?**
- Sur mobile : bien toucher au centre des cœurs
- Sur desktop : cliquer sur les cœurs colorés

**Déploiement échoue ?**
- Vérifier avec `vercel --version` que CLI est à jour
- Essayer `vercel --force` pour forcer le redéploiement

## 📄 Licence

Créé avec amour pour Samuella ❤️

---

**Joyeuse Saint Valentin !** 🌹
