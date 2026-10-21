# Tycoon Lab : page de vote

Page statique (un seul `index.html`, aucun build) pour le test des 3 concepts de jeu idle.
Chaque visiteur choisit un jeu et laisse son email ; les inscriptions et les clics sont enregistrés dans Supabase
(tables `idle_signups` et `idle_events`, via les fonctions `idle_signup` et `idle_track`, en écriture seule).

- Lien de bio à utiliser : `https://<domaine>/?src=tiktok` (ou `youtube`, `instagram`) pour savoir d'où viennent les inscriptions.
- Déploiement Vercel : importer le dépôt, preset "Other", aucune commande de build.
