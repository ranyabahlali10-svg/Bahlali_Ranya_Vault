# Structure et Outils

L'organisation du Vault a été pensée pour être logique et évolutive.

### 1. Hiérarchisation des dossiers
J'ai numéroté les dossiers (0 à 9) pour forcer un ordre de lecture. Cela permet à n'importe qui d'ouvrir le projet et de savoir par où commencer (les persos, puis les thèmes, puis la doc).

### 2. Plugins clés
- **Dataview** : C'est le moteur du projet. Il me permet d'agréger les données des personnages (statut, affiliation) sans avoir à mettre à jour mes listes manuellement.
- **Canvas** : Je l'ai utilisé pour cartographier les relations complexes de Baltimore. C'est l'outil parfait pour montrer que tout le monde est lié dans "Le Jeu".
- **Templates** : J'ai créé des modèles dans `0_META` pour que chaque fiche personnage soit identique. C'est ce qui garantit que les données sont propres pour Dataview.

### 3. Webscraping
Pour éviter les erreurs et gagner en efficacité, j'ai importé une base de données issue du webscraping. J'ai ensuite retraité ces données pour les adapter au format Markdown d'Obsidian.