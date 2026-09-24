# TempDelos

Dépôt de travail partagé — IA Langelier & James (NonameCompanie).

## Contenu

- `multi-agent-saas/` — MVP du SaaS multi-agent : gestion d'agents IA (installation / désinstallation / duplication / extraction .zip), orchestrateur et 3 agents simulés (Commercial, Support, Finance), thème clair/sombre.
  - Démo en ligne : https://code-079041b87ce.fly.dev
  - Projet source (Delos Code) : Multi-Agent SaaS MVP — NonameCompanie
  - Build statique complet livré dans le Drive (zip), prêt à déposer sur n'importe quel hébergement (cPanel/o2switch, GitHub Pages…)

## Roadmap

1. ~~MVP démo~~ ✅
2. Déploiement sur hébergement français (o2switch — myenvtest.immersive-lab.fr)
3. Moteur IA réel (clé API), multi-utilisateur, facturation

## Déployer sur o2switch (cPanel)

Dézippez `multi-agent-saas-dist.zip` et uploadez le contenu de `dist/` dans `public_html` du sous-domaine via le Gestionnaire de fichiers de cPanel (bouton Upload ou glisser-déposer). Aucune dépendance serveur : c'est du statique, Node.js n'est même pas nécessaire pour cette version.
