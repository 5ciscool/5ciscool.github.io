# 5c

Mon site perso. Une seule page, thème vert, faite en HTML, CSS et JavaScript, sans framework.

## Ce qu'il y a sur le site

- **Profil** : ma photo, mon pseudo `.5c_.` (clique dessus pour le copier) et une phrase qui s'écrit toute seule.
- **Liens** : TikTok et Discord.
- **Statut Discord en direct** : la case « Status » montre mon vrai statut (online, idle, do not disturb, offline) et mon statut perso ou le jeu auquel je joue. Il se met à jour toutes les 30 secondes.
- **Achievements** : des succès à débloquer, avec des secrets. Ils sont gardés dans le navigateur, donc ils restent quand tu reviens.
- **Joints cliquables** : clique dessus pour voir ce qui se passe.
- **Test de frappe** : 60 secondes pour mesurer ta vitesse (mots par minute).
- **Test de réaction** : mesure ton temps de réaction en millisecondes.
- **Terminal caché** : appuie sur la touche `` ` `` pour l'ouvrir. Tape `help` pour voir les commandes.
- **Mode lite** : désactive les animations si le site est lent (commande `perf`).

## Comment ça marche

Tout est dans un seul fichier : `index.html`. Il n'y a rien à installer.

Pour tester sur ton ordinateur, ouvre `index.html` dans ton navigateur.

## Mettre le site en ligne

Le site est hébergé avec **GitHub Pages** :

1. Va dans **Settings → Pages**.
2. Choisis la branche `main` et le dossier `/ (root)`.
3. Enregistre. Ton site sera sur `https://TON-PSEUDO.github.io/`.

## Statut Discord

Le statut utilise [Lanyard](https://github.com/Phineas/lanyard), un service gratuit.

1. Rejoins le serveur Lanyard : `discord.gg/lanyard`.
2. Dans `index.html`, cherche `DISCORD_ID` et mets ton identifiant Discord (des chiffres).

## Changer le contenu

- **Pseudo et textes** : cherche le texte dans `index.html` et change-le.
- **Phrases qui s'écrivent** : cherche `phrases=` dans le fichier.
- **Liens TikTok et Discord** : cherche `tiktok.com` et `discord.gg`.

## Remarque

Les achievements et les meilleurs scores sont gardés dans le navigateur de chaque visiteur (`localStorage`). Ils ne sont pas partagés entre deux appareils.
