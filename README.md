# Shopify + Astro + React

[![Netlify Status](https://api.netlify.com/api/v1/badges/00c79ab2-364d-4c1d-923b-ed0a9a3b4d2b/deploy-status)](https://app.netlify.com/sites/shopify-astro/deploys)

Site web shopify sous [Astro](https://astro.build) et React.
Installer [Netlify CLI](https://cli.netlify.com/) pour le fonctionnement des fonctions serverless.
## Monter le site

[![Déployer sur Netlify](https://www.netlify.com/img/deploy/button.svg)](https://app.netlify.com/start/deploy?repository=https://github.com/Erinell/shopify-react-astro)

Cliquer sur ce bouton pour déployer le site sur Netlify. Créer un fichier `.env` à la racine du projet et ajouter ceci :

```bash
SHOPIFY_STOREFRONT_API_TOKEN=example
SHOPIFY_API_ENDPOINT=https://exampleshopify/graphql.json
```

## Commandes

| Command         | Action                                  |
| :-------------- | :-------------------------------------- |
| `npm install`   | Installer les dépendances               |
| `npm run start` | Démarrer un serveur local               |
| `npm run build` | Compiler pour production dans `./dist/` |
