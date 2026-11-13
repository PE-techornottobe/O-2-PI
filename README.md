# Ô de Péi — dépôt de travail

Ce dépôt sert à centraliser le code et les évolutions de la plateforme pédagogique Ô de Péi.

## État initial — 13 novembre 2026
Le dépôt était vide au début de l'audit. La version de référence disponible séparément est une archive exportée de Lovable (`la-petite-ecole-du-vin-site.zip`). **Le code de cette archive n'a pas encore été importé ici.** Ce README ne constitue pas un déploiement.

## Architecture visée
- **Interface** : React, TypeScript, TanStack Router/Start, Vite et Tailwind (d'après l'export Lovable).
- **Contenus** : données pédagogiques structurées et versionnées, séparées des composants visuels.
- **Cartographie** : moteur de cartes indépendant, données géographiques sourcées, sans tracés inventés.
- **Évaluations** : quiz accessibles, avec export possible vers Moodle ; aucune synchronisation de notes n'est encore active.
- **Conception** : maquettes Figma, composants réutilisables et interfaces adaptées au mobile.

## Étapes de migration
1. Confirmer que l'export Lovable est bien la dernière version de production.
2. Importer les fichiers sources dans une branche dédiée, sans secrets ni fichiers générés.
3. Vérifier les dépendances, les ressources médias, le build et les routes.
4. Créer des composants cartographiques réutilisables, puis des tests.
5. Préparer l'intégration Moodle et la publication, après validation.

## Précautions
Ne jamais committer de mots de passe, clés API, données personnelles d'apprenants, exports de bases de données ou jetons Moodle. Toute modification majeure doit être examinée avant mise en production.
