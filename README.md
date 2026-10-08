# streetnow-legal

Dépôt **public** dédié aux pages légales et publiques de l’application
StreetNow, publié avec GitHub Pages.

## Contenu de ce dépôt

Ce dépôt ne contient **que** des pages publiques, en HTML et CSS statiques :

- `index.html` — page d’accueil minimale (liste des ressources) ;
- `privacy-policy/index.html` — page « Politique de confidentialité de StreetNow » ;
- `delete-account/index.html` — page « Supprimer votre compte StreetNow » ;
- `assets/styles.css` — feuille de style unique (aucune dépendance externe).

Ce dépôt ne contient **aucun** code source de l’application, **aucune**
configuration privée, **aucune** clé d’API et **aucun** secret. Les pages
n’embarquent ni JavaScript, ni cookie, ni outil de mesure d’audience.

## Contact

Adresse de support affichée sur la page et utilisée par le lien `mailto:` :
`streetnow888@gmail.com`.

## Mise en ligne (GitHub Pages)

1. Pousser ce dépôt sur `LETSFOOT/streetnow-legal` (branche `main`).
2. Dans le dépôt GitHub : **Settings → Pages**.
3. *Build and deployment* → **Source : Deploy from a branch**.
4. **Branch : `main`** et **Folder : `/ (root)`**, puis **Save**.
5. Après quelques dizaines de secondes, la page est disponible à :

   - accueil : `https://letsfoot.github.io/streetnow-legal/`
   - politique de confidentialité : `https://letsfoot.github.io/streetnow-legal/privacy-policy/`
   - suppression de compte : `https://letsfoot.github.io/streetnow-legal/delete-account/`

## Vérification locale

Ouvrir directement `index.html` dans un navigateur, ou servir le dossier :

```powershell
python -m http.server 8080
```

puis ouvrir `http://localhost:8080/delete-account/`.
