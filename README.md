# ÉcoMaster L1 — Révision & Entraînement

Application web mobile de révision dédiée à l'analyse économique et à la macroéconomie en L1. Ce projet est indépendant des applications de mathématiques et de sport.

## Fonctionnalités
- 7 séances de révision avec fiches synthétiques et listes de compétences.
- Flashcards classées par séance, auto-évaluation et filtre « à revoir ».
- Recherche dans les notions, définitions et nuances des flashcards.
- QCM par séance, session rapide, examen complet et reprise des erreurs.
- Schémas SVG animés intégrés aux questions concernées.
- Tableau de bord de progression par séance.
- Sauvegarde locale automatique, export JSON et import de progression.
- Mode sombre et installation comme application sur téléphone (PWA).

## Déploiement GitHub Pages
1. Ouvrir **Settings → Pages**.
2. Choisir **Deploy from a branch**, branche `main`, dossier `/ (root)`.
3. Enregistrer puis attendre la publication.
4. Ouvrir l'URL GitHub Pages sur Android avec Chrome et choisir **Installer l'application** / **Ajouter à l'écran d'accueil**.

## Données et mode hors ligne
La progression est conservée dans le stockage local du navigateur de l'appareil. Elle n'est pas synchronisée entre appareils : utiliser **Progrès → Exporter** pour sauvegarder et **Importer** pour restaurer. Après un premier chargement en ligne, le service worker met en cache l'application et ses dépendances CDN pour permettre une utilisation hors ligne partielle ; les ressources externes non encore chargées nécessitent une connexion.
