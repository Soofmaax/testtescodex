# Nutrition Need Heroes

Homepage statique de **Nutrition Need Heroes**, prête à être publiée sur GitHub Pages.

## Voir le site localement

```bash
npm start
```

Ouvrez ensuite <http://localhost:4173>.

## Publication sur GitHub Pages

Le workflow `.github/workflows/deploy-pages.yml` publie automatiquement le site à chaque push sur `main`.

1. Créez un dépôt GitHub **public** et poussez cette branche sur `main`.
2. Dans le dépôt GitHub, ouvrez **Settings → Pages**.
3. Sous **Build and deployment → Source**, choisissez **GitHub Actions** et enregistrez.
4. Ouvrez **Actions → Deploy to GitHub Pages**, puis lancez **Run workflow** sur `main`.

Cette activation manuelle n'est nécessaire qu'une fois. Elle évite l'erreur `Resource not accessible by integration` que GitHub peut renvoyer lorsqu'un workflow essaie de créer lui-même le site Pages.

Le site sera alors disponible à l'adresse :

```text
https://VOTRE-COMPTE.github.io/NOM-DU-DEPOT/
```

Le workflow peut aussi être relancé manuellement depuis **Actions → Deploy to GitHub Pages → Run workflow**.
