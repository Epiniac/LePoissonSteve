# 🌐 Projet Web Ultra-Léger — Avril/Mai 2025

## 🎯 Objectif
Développer une application web statique, ultra-légère et 100% accessible, conçue pour fonctionner sur de vieilles machines et avec des connexions lentes.  
L’application respecte les normes WCAG 2.1 (niveau AAA ciblé), sans frameworks modernes, et est déployée via GitHub Pages.

## 🧩 Thème & Problématique
**Thème :** Bounty Hunter. 
**Objectif :** Fournir aux chasseurs de primes un outil numérique minimaliste pour les aider à gérer leurs missions, améliorer leur sécurité et assurer une meilleure conformité légale.​
**Problématique :** Comment améliorer la sécurité, l'efficacité et la conformité légale des chasseurs de primes tout en respectant les contraintes techniques d'une application web ultra-légère et accessible ?

> _"Notre application répond à un besoin réel de ce corps de métier en apportant une solution simple, rapide et accessible."_

## 🛠️ Fonctionnalités clés

**Gestion des missions** : Interface simple pour enregistrer et suivre les missions en cours, avec des informations essentielles sur les fugitifs.​

**Checklist de conformité légale** : Guides interactifs rappelant les procédures légales à suivre selon l'État concerné.​

**Journal de bord sécurisé** : Possibilité de consigner les actions entreprises lors de chaque mission, utile en cas de vérification ou de litige.​

**Ressources et formations** : Accès à des documents et vidéos de formation sur les meilleures pratiques et la gestion des risques.

> _"C'est border..."_

## 👥 Équipe (Groupe de 5)
- Sabrina Attos - sabrina.attos@gmail.com
- Barbot Jim - jimbarbot55@gmail.com
- Moran Diego - diegoeman00@gmail.com
- Janus Alexis - janusalexis@gmail.com
- Jacques Chen - jacqueschen92@gmail.com

> Chaque section du code est annotée avec des commentaires d'identification :  
> `<!-- Début [section] – Prénom Nom -->` / `<!-- Fin [section] – Prénom Nom -->`

---

## ⚙️ Stack Technique

- HTML5 sémantique
- CSS3 sobre et responsive (sans framework)
- JavaScript minimal (avec fallback si JS désactivé)
- Déploiement via **GitHub Pages**
- CI/CD léger avec **GitHub Actions**

---

## ✅ Accessibilité & Performances

- Navigation 100% clavier
- Lecture linéaire compatible lecteurs d'écran
- Contraste conforme au **niveau AAA** des WCAG 2.1
- Rôles ARIA uniquement si nécessaires
- Fallbacks CSS pour compatibilité navigateur maximale
- Polices web-safe ou hébergées localement
- Aucune dépendance externe inutile (pas de frameworks, CDN ou librairies JS tierces)

---

## 🚀 Déploiement

- Accès en ligne : [https://votre-utilisateur.github.io/nom-du-projet](https://votre-utilisateur.github.io/nom-du-projet)
- Mise en ligne automatique via GitHub Actions après chaque *push* sur la branche `main`

---

## 🧪 Audits & Tests

- Accessibilité testée avec Lighthouse et axe DevTools
- Performances mesurées avec PageSpeed Insights
- Tests de compatibilité avec navigateurs anciens (Chrome 49, Firefox ESR, IE11)
- Tests en conditions "3G lente" avec les outils de développement

---

## 📁 Arborescence du projet

```bash
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── assets/
│   ├── images/
│   └── fonts/
├── .github/
│   └── workflows/
│       └── deploy.yml
└── README.md
