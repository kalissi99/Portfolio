# Portfolio — Yaye Fatou Gueye

Site statique (HTML/CSS/JS, aucune dépendance) prêt pour Vercel.

## Mettre en ligne sur Vercel

1. Crée un dépôt GitHub `portfolio` et envoie ce dossier :
   git init
   git add .
   git commit -m "Portfolio 2026"
   git branch -M main
   git remote add origin https://github.com/kalissi99/portfolio.git
   git push -u origin main
2. Va sur vercel.com, connecte-toi avec GitHub, clique « Add New… > Project ».
3. Importe le dépôt `portfolio`. Framework Preset : « Other ». Ne change rien d'autre.
4. Clique « Deploy ». Ton site est en ligne sur https://portfolio-xxx.vercel.app.
5. (Optionnel) Settings > Domains pour renommer en `yayefatou.vercel.app`.

Chaque `git push` met le site à jour automatiquement.

## Français / English
- Le bouton FR | EN dans le menu traduit toute la page et change le CV téléchargé.
- Lien direct vers la version anglaise à envoyer aux recruteurs étrangers : https://ton-site.vercel.app/?lang=en
- Pour modifier un texte : le français est dans la balise, l'anglais dans l'attribut data-en juste à côté.
- CV : assets/CV-Yaye-Fatou-Gueye-FR.pdf et assets/CV-Yaye-Fatou-Gueye-EN.pdf (remplace les fichiers en gardant le même nom pour mettre à jour).

## À compléter
Cherche « À COMPLÉTER » et « À VÉRIFIER » dans index.html :
- lien direct du dépôt card-fraud-lab et tes vrais résultats (rappel, précision) ;
- le nom exact des datasets Kaggle utilisés.

## Fichiers
- index.html : tout le site
- assets/ : photos optimisées + CV en PDF (FR et EN)
- vercel.json : en-têtes de sécurité et cache
