# Multi-Agent SaaS MVP — NonameCompanie

Démo SaaS en français pour gérer, installer et orchestrer plusieurs agents IA simulés.

## Contenu

- `multi-agent-saas/` : application de démonstration
  - `dist/` : build statique prêt à déployer (upload du contenu dans `public_html` suffisant)
  - `build-source.html` : point d'entrée HTML du build
- `public/` : copie des fichiers statiques du build (racine déployable)
- `docs/` : documentation du projet

## Déploiement sur o2switch (cPanel)

L'application est 100% statique : déployez le contenu de `public/` (ou `multi-agent-saas/dist/`) dans le dossier `public_html` de votre sous-domaine via le Gestionnaire de fichiers de cPanel. Aucun Node.js ni SSH requis.

## Agents inclus

- Commercial : devis, pipeline, relances
- Support : tickets, FAQ, escalade
- Finance : factures, impayés, trésorerie
- Orchestrateur : routage des demandes

Réponses simulées (aucune clé API branchée) — MVP de validation d'expérience.
