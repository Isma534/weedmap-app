# WeedMap - projet Capacitor

Ce dossier contient ton site WeedMap prêt à être transformé en vraie app iOS (.ipa)
via Capacitor + Codemagic, sans avoir besoin d'un Mac.

## Etapes

1. Dépose TOUT le contenu de ce dossier (garde la structure des sous-dossiers) sur GitHub,
   dans un nouveau repository (voir les instructions données par Claude).
2. Connecte ce repository à Codemagic (codemagic.io).
3. Choisis le workflow "Capacitor" (ou "iOS App - Capacitor") proposé par Codemagic.
4. Connecte ton Apple ID pour la signature automatique.
5. Lance le build. Le fichier .ipa sera disponible en téléchargement à la fin.

## Contenu

- `www/index.html` : ton site WeedMap tel quel (avec tes clés Supabase déjà dedans).
- `package.json` : liste des briques nécessaires (Capacitor).
- `capacitor.config.json` : nom de l'app ("WeedMap") et dossier du site web ("www").

Codemagic va automatiquement installer les dépendances, créer le projet iOS,
et compiler l'app à partir de ces fichiers.
