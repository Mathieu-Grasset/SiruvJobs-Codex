# siruvjobs — Jobs Codex / Codex des métiers

Page statique bilingue (EN par défaut, FR au choix). Aucun serveur, aucune dépendance : `index.html` + dossier `img/`.

## Liens à utiliser (remplace `UTILISATEUR` et `DEPOT`)

| Où | Lien |
|---|---|
| Description CurseForge / vidéo EN | `https://UTILISATEUR.github.io/DEPOT/` (ou `...?lang=en`) |
| Description de la vidéo FR | `https://UTILISATEUR.github.io/DEPOT/?lang=fr` |
| Un métier précis | `...?lang=fr#mineur` (ids : batisseur, bucheron, chasseur, eleveur, enchanteur, explorateur, fermier, mineur, pecheur, commandes, general) |

Priorité de langue : paramètre `?lang=` de l'adresse > dernier choix du visiteur (bouton EN/FR) > anglais.

## Mise en ligne (GitHub Pages)

1. Créer un dépôt public (ex. `siruvjobs-codex`) et y déposer le contenu de ce dossier (`index.html`, `img/`, `.nojekyll`).
2. Dépôt > Settings > Pages > Source : « Deploy from a branch », branche `main`, dossier `/ (root)`.
3. Après une minute, la page est sur `https://UTILISATEUR.github.io/siruvjobs-codex/`.

## CurseForge

Les descriptions CurseForge n'exécutent pas de scripts : on y met un lien vers la page (en bas de la description, CurseForge passe par une page d'avertissement « linkout »). Le lien peut aussi aller dans le champ « Wiki » des paramètres du projet.
