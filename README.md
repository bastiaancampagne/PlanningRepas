# PlanningRepas PWA v4

Version modernisée du PlanningRepas PWA v3 fourni.

Déploiement : décompresser puis envoyer le CONTENU du dossier à la racine du dépôt GitHub Pages.
Après déploiement, faire une fois **Ctrl+F5** pour forcer le nouveau cache.

La maquette de référence est incluse dans `maquette/PlanningRepas_maquette_v4.png`.


## Version 4.3 — import simplifié et stock

Le PDF d'import peut désormais se limiter à :

07/09/2026

Midi : Poulet rôti, pommes de terre et carottes
Personnes : 6

Soir : Soupe de légumes et tartines au fromage
Personnes : 5

L'application recherche ensuite la recette, adapte les quantités, demande validation,
puis compare les besoins au stock saisi dans la page « Stock » avant d'établir la liste de courses.

Les recherches de recettes inconnues utilisent TheMealDB. Les résultats en ligne sont à vérifier,
notamment parce que le nombre de portions d'origine n'est pas toujours fourni.
