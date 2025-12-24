# Méthodologie de Collecte (Webscraping)

Pour construire ce Vault, j'ai utilisé des techniques de **webscraping** afin d'extraire les données du Wiki officiel de *The Wire*.

### Pourquoi le Webscraping ?
- **Efficacité** : Récupérer automatiquement les informations de plus de 35 personnages sans saisie manuelle.
- **Précision** : Éviter les erreurs de frappe dans les noms ou les affiliations, ce qui est crucial pour le bon fonctionnement des requêtes **Dataview**.
- **Industrialisation** : Montrer une capacité à traiter un volume de données externe pour l'intégrer dans un environnement de connaissance personnel.

### Outils et Processus
1. **Source** : [The Wire Wiki](https://thewire.fandom.com/wiki/The_Wire_Wiki).
2. **Extraction** : Utilisation d'un sélecteur HTML pour récupérer les champs : *Nom*, *Affiliation*, *Saisons* et *Statut*.
3. **Transformation** : Conversion du format brut (CSV/HTML) vers le format Markdown compatible avec Obsidian.