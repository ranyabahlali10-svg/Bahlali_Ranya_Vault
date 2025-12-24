# Configuration Technique du Vault

Cette note récapitule les réglages effectués pour rendre ce projet fonctionnel et automatisé.

### 1. Gestion des Modèles (Templates)
- **Emplacement :** `0_META/Templates`.
- **Usage :** Utilisation du module principal "Modèles" pour générer chaque nouvelle fiche. Cela garantit que les métadonnées sont toujours présentes pour alimenter les tableaux de bord.

### 2. Organisation des Médias 
- **Stockage :** Toutes les images et captures d'écran sont centralisées pour éviter de polluer les dossiers d'analyse.
- **Format :** Utilisation de liens internes pour afficher les visuels dans les fiches personnages et le Canvas.

### 3. Automatisation des Métadonnées
- Les propriétés comme `statut` ou `affiliation` sont standardisées.
- **But :** Permettre au plugin **Dataview** de filtrer les personnages par groupe (ex: Clan Barksdale) ou par état (ex: Mort/Vivant) de manière instantanée.