# Taux des livrets réglementés — Upsola

Ce dépôt publie un seul fichier, `taux.json`, lu par l'appli Upsola pour préremplir les taux
du Livret A, du LDDS, du LEP et du CEL. Il est publié automatiquement par Cloudflare Pages
(taux.upsola.app) à chaque modification.

Format : `historique` liste chaque changement (`date_effet`, `taux` en %, `source`).
Les taux sont fixés par arrêté et révisés en principe le 1er février et le 1er août.
