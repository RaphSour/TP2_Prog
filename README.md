# LayerStatsWidget

## Description

**LayerStatsWidget** est un plugin QGIS développé dans le cadre du cours GMQ580 – Géo-Informatique II. Ce widget s’intègre comme un panneau dockable dans QGIS et permet d’afficher en temps réel des statistiques de base sur la couche vectorielle active : nom, type de géométrie, nombre d'entités, surface totale (pour les polygones) ou longueur totale (pour les lignes).

---

## Installation

1. **Télécharger le plugin** :
   - Cloner ce dépôt Git ou télécharger le dossier `LayerStatsWidget/`.

2. **Placer le plugin dans le répertoire QGIS** :
   - Copier le dossier `LayerStatsWidget/` dans le répertoire des plugins QGIS :
     - **Windows** : `C:\Users\<votre_nom>\AppData\Roaming\QGIS\QGIS3\profiles\default\python\plugins\`
     - **Linux/Mac** : `~/.local/share/QGIS/QGIS3/profiles/default/python/plugins/`

3. **Activer le plugin** :
   - Lancer QGIS.
   - Aller dans le menu **Extensions** > **Gérer et installer des extensions**.
   - Rechercher **LayerStatsWidget** et cliquer sur **Activer**.

---

## Utilisation

1. Charger une ou plusieurs couches vectorielles dans QGIS (shapefile, GeoJSON, etc.).
2. Le widget apparaîtra dans un panneau dockable (dans le menu **Affichage** > **Panneaux**).
3. Dès qu'une couche est sélectionnée, le widget affiche automatiquement :
   - Le nom de la couche
   - Le type de géométrie (points, lignes, polygones)
   - Le nombre total d'entités
   - La surface totale (pour les polygones) ou la longueur totale (pour les lignes), dans l’unité de la couche

---

## Dépendances

- Python ≥ 3.x
- QGIS ≥ 3.x
- PyQGIS (inclus avec QGIS)

---

## Auteurs

- Jérémie Gagnon
- Raphaël Sourceaux

Projet réalisé pour **GeoInnovations** dans le cadre du **Travail Dirigé #2** du cours GMQ580.