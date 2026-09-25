# PPM RT — Pôle INFRA

Démonstration publique du tableau de bord de pilotage de portefeuille de
RT Ingénierie — Pôle INFRA.

👉 **https://sergaey.github.io/ppm-rt-pole-infra/**

## Ce que contient cette version

Une application web autonome, en un seul fichier HTML. Portefeuille projets,
cockpit d'indicateurs, passeports projet, capacité et plan de charge, phasing
budgétaire, GEDT.

**Même application que celle du poste de travail** : même code, même numéro de
version, mêmes évolutions. La fabrication compare l'empreinte du code des deux
fichiers à chaque publication et refuse de publier si elle diffère.

**Les données publiées sont fictives**, et le resteront : projets, membres,
budgets et sociétés sont inventés. Aucune donnée réelle n'est publiée ici.

**Pour travailler sur ses propres données** : `⇄ Données → Importer JSON`, puis
son `_ppm_state.json`. Le fichier est lu par le navigateur et n'est envoyé
nulle part ; les données restent sur le poste du visiteur, et rien n'est
téléversé. Il n'y a ni compte ni serveur : pour l'équipe et le fichier de
données commun, c'est le kit local `Lancer_PPM.bat`.

## Publication

Ce dépôt est **généré**. Il ne se modifie pas à la main : son contenu est
produit depuis le dépôt de travail, d'où les données nominatives sont retirées
avant publication.

GitHub Pages : Settings → Pages → Branch `main` / dossier `/ (root)`.
