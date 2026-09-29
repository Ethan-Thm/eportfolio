# Ethan Thomas — portfolio

Portfolio bilingue (français / anglais) en HTML, CSS et JavaScript sans dépendances ni étape de compilation.

## Prévisualiser

Ouvrir `index.html` dans un navigateur. Pour tester comme un site hébergé, lancer un serveur statique depuis ce dossier, par exemple :

```sh
python3 -m http.server 8000
```

Puis ouvrir `http://localhost:8000`.

## Publier gratuitement avec GitHub Pages

1. Créer un dépôt public GitHub nommé `eportfolio` (sans README généré automatiquement).
2. Depuis ce dossier, initialiser Git et publier les fichiers :

   ```sh
   git init -b main
   git add .
   git commit -m "Create bilingual portfolio"
   git remote add origin https://github.com/<identifiant>/eportfolio.git
   git push -u origin main
   ```

3. Dans **Settings → Pages**, choisir **Deploy from a branch**, la branche `main` et le dossier `/ (root)`.
4. Attendre la fin de la publication GitHub Pages. L’adresse aura la forme `https://<identifiant>.github.io/eportfolio/`.

Le site n’utilise pas d’outils tiers, de polices distantes, de clés API ou de processus de compilation. Pour modifier les textes, éditer les traductions dans `script.js`. Les CV téléchargeables se trouvent à la racine du site.

## Mise à jour des informations

Le texte de disponibilité de stage des CV indique juillet–septembre 2026 et n’a pas été repris dans le site, car cette période arrive à son terme au moment de la refonte (septembre 2026). Mettre à jour les PDF avant de les republier si cette information doit rester visible.
