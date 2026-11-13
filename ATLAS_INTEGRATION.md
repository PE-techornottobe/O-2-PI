# Atlas Bordeaux — préparation d'intégration V0.2

Un paquet complet basé sur l'export Lovable du 13 novembre 2026 a été préparé séparément : `O_de_Pei_Lovable_Atlas_Bordeaux_V0_2.zip`.

## Contenu réalisé dans le paquet
- Onglet **Atlas interactif** ajouté à la route existante `/vin/bordeaux`.
- Trois fiches : Pauillac, Pomerol, Saint-Émilion.
- Carte OpenStreetMap embarquée, sélection d'appellation, chronologies, terroirs, domaines et quiz corrigés.
- Données JSON distinctes de la présentation.

## Limites
- La carte utilise des points centraux indicatifs, pas des délimitations AOC ni des parcelles cadastrales.
- Les questions ne synchronisent pas les notes avec Moodle.
- Le build n'a pas encore été validé : dépendances non installées et certains médias de l'export sont représentés par des fichiers .asset.json.
- Le dépôt GitHub n'héberge pas encore l'ensemble des sources Lovable ; ne pas considérer cette branche comme une version déployable.

## Étapes restantes
1. Importer l'intégralité des sources Lovable depuis l'archive V0.2.
2. Vérifier et restaurer les ressources médias manquantes.
3. Installer les dépendances et exécuter build, tests et vérification visuelle.
4. Ajouter les polygones officiels INAO sourcés et vérifier les contenus historiques.
5. Faire relire et fusionner les modifications, puis publier.
