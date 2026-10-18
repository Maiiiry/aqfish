# Captures de la nuit 2026-10-17

| Champ | Valeur |
|---|---|
| Branche | `nuit/2026-10-17-pipeline-pixel-art` |
| PR | #17 |
| Commit (code applicatif) | `641a257` (le commit QA `878acd9` n'ajoute que des tests e2e) |
| Graine | 42 |
| Temps | 30 s |
| Rendu | Chromium sans GPU (SwiftShader), 1280 × 720, pixel ratio 1 |
| Commande | `CAPTURE_DIR=… npm run captures` |

Première série en pixel art : cible basse résolution (`PIXEL_SIZE = 3`) et passe palette.
Contrôle par script : 0 couleur hors des 34 couleurs de `render/palette.ts`, 0 pixel hors
d'un bloc 3 × 3 uniforme, sur les 5 angles (5 à 7 couleurs par image). Le sable retrouve
`sable` #c9b38a (il tirait au vert-gris dans la série 2026-10-16). Le dossier `dev/` contient
les captures jointes par Dev à la PR.
