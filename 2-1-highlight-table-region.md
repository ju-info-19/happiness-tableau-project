# Partie 2 – Tâche 1 : Tableau des points forts du score moyen par région

## Objectif
Créer une highlight table affichant le score de bonheur moyen pour chaque région,
servant de filtre dans le tableau de bord.

## Procédure

1. **Créer une nouvelle feuille** nommée `Score moyen par région`.
2. **Placer les champs** :
   - Glisser `Region` sur **Lignes**.
   - Glisser `Happiness Score` sur **Texte** (dans la zone Marks).
   - L'agrégation par défaut est `SUM` ; passez-la à `AVG` (clic droit sur la pilule > Mesure > Moyenne).
3. **Trier** : clic droit sur la pilule `Region` > Trier > Décroissant par `AVG(Happiness Score)`.
4. **Type de visualisation** : panneau "Montre‑moi" > **Tableau de points forts**.
5. **Mise en forme** :
   - Titre : `Score moyen de bonheur par région (2015‑2023)`.
   - Ajustez la taille du texte et l'alignement.
6. **Option filtre** : une fois placée dans le tableau de bord, activez l'icône **Utiliser comme filtre** (entonnoir).

## Vérification
- Une ligne par région, tri décroissant.
- La table met en évidence les valeurs élevées/faibles.