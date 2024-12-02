# Monorepo Next.js + AdonisJS avec Turborepo

<p align="center">
  <img src="https://user-images.githubusercontent.com/4060187/196936104-5797972c-ab10-4834-bd61-0d1e5f442c9c.png" alt="Turborepo Logo" height="60">
  <img src="https://upload.wikimedia.org/wikipedia/commons/8/8e/Nextjs-logo.svg" alt="Next.js Logo" height="60">
  <img src="https://static.adevait.com/assets/skills/logos/adonisJS.svg" alt="AdonisJS Logo" height="60">
</p>

Ce projet est un **monorepo** combinant un frontend **Next.js** et un backend **AdonisJS**, le tout géré avec **Turborepo** pour une organisation et des performances optimales.

---

## 📂 Structure du projet

```bash
monorepo-next-adonis/
├── apps/
│   ├── adonis/   # Application backend (AdonisJS)
│   └── nextjs/   # Application frontend (Next.js)
├── node_modules/ # Modules partagés
├── package.json  # Gestion des dépendances et des workspaces
├── turbo.json    # Configuration de Turborepo
└── .gitignore    # Fichiers et dossiers ignorés par Git