# Nutrition Need Heroes

Homepage statique de **Nutrition Need Heroes**, prête à être publiée sur GitHub Pages.

## Voir le site localement

```bash
npm start
```

Ouvrez ensuite <http://localhost:4173>.

## Publication sur GitHub Pages

Le workflow `.github/workflows/deploy-pages.yml` publie automatiquement le site à chaque push sur `main`.

1. Créez un dépôt GitHub et poussez cette branche sur `main`.
2. Ouvrez l'onglet **Actions** et attendez la fin du workflow **Deploy to GitHub Pages**.

Le workflow active lui-même GitHub Pages si le dépôt ne possède pas encore de site Pages. Si votre organisation interdit cette activation automatique, ouvrez **Settings → Pages** puis choisissez **GitHub Actions** sous **Build and deployment → Source** avant de relancer le workflow.
2. Dans le dépôt GitHub, ouvrez **Settings → Pages**.
3. Sous **Build and deployment → Source**, choisissez **GitHub Actions**.
4. Ouvrez l'onglet **Actions** et attendez la fin du workflow **Deploy to GitHub Pages**.

Le site sera alors disponible à l'adresse :

```text
https://VOTRE-COMPTE.github.io/NOM-DU-DEPOT/
```

Le workflow peut aussi être relancé manuellement depuis **Actions → Deploy to GitHub Pages → Run workflow**.
