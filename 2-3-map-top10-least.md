# Partie 2 – Tâche 2 : Carte des 10 pays les plus heureux

## Objectif
Carte avec fond "Normal" affichant les 10 pays au score moyen de bonheur le plus élevé.
Infobulles : pays, région, score.

## Procédure

### Paramètre
1. Créez un paramètre **`Top N Happy`** (type Entier, valeur 10, plage 1‑20).

### Champ calculé « Pays Top Happy »
2. Créez un champ calculé :
   ```tableau
   IF INDEX() <= [Top N Happy] THEN [Country] END