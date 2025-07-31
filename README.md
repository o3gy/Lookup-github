<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Lookup GitHub - README</title>
</head>
<body style="background:#0d1117; color:#c9d1d9; font-family:Segoe UI, Tahoma, Geneva, Verdana, sans-serif; margin:2rem auto; max-width:720px; line-height:1.6; padding:0 1rem;">

<header style="display:flex; align-items:center; gap:0.8rem; margin-bottom:1.5rem;">
  <img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="Logo GitHub" width="36" height="36" style="flex-shrink:0;" />
  <h1 style="color:#58a6ff; font-weight:700; font-size:2.4rem; margin:0;">Lookup GitHub</h1>
</header>

<p>Un outil simple pour récupérer et sauvegarder les données publiques d’un utilisateur GitHub, en local et avec résumé console.</p>

<h2 style="color:#58a6ff; border-bottom:2px solid #30363d; padding-bottom:0.3rem; margin-top:2rem;">Fonctionnalités</h2>
<ul>
  <li>Infos de profil (nom, bio, followers, repos...)</li>
  <li>Détails des dépôts et gists publics</li>
  <li>Liste complète des followers et following</li>
  <li>Historique des événements publics</li>
  <li>Export automatique dans des fichiers texte</li>
  <li>Affichage résumé stylé dans la console</li>
</ul>

<h2 style="color:#58a6ff; border-bottom:2px solid #30363d; padding-bottom:0.3rem; margin-top:2rem;">Installation</h2>
<pre style="background:#161b22; padding:1rem; border-radius:8px; overflow-x:auto;">
<code>git clone https://github.com/ton-utilisateur/lookup-github.git
cd lookup-github
pip install -r requirements.txt
</code>
</pre>

<h2 style="color:#58a6ff; border-bottom:2px solid #30363d; padding-bottom:0.3rem; margin-top:2rem;">Utilisation</h2>
<p>Lance le script et entre le nom d’utilisateur GitHub :</p>
<pre style="background:#161b22; padding:1rem; border-radius:8px; overflow-x:auto;">
<code>python main.py
</code>
</pre>
<p>Les fichiers seront sauvegardés dans <code>output/&lt;username&gt;/</code></p>

<h2 style="color:#58a6ff; border-bottom:2px solid #30363d; padding-bottom:0.3rem; margin-top:2rem;">Fichiers créés</h2>
<ul>
  <li><code>info.txt</code> — résumé général</li>
  <li><code>followers.txt</code> et <code>following.txt</code> — listes d’abonnés</li>
  <li><code>repos.txt</code> — détails des dépôts</li>
  <li><code>gists.txt</code> — gists publics</li>
  <li><code>events.txt</code> — historique des événements</li>
</ul>

<h2 style="color:#58a6ff; border-bottom:2px solid #30363d; padding-bottom:0.3rem; margin-top:2rem;">Limitations</h2>
<ul>
  <li>API GitHub non authentifiée → limite d’appels par heure</li>
  <li>Données privées non accessibles</li>
  <li>Connexion internet nécessaire</li>
</ul>

<footer style="margin-top:3rem; font-size:0.85rem; color:#8b949e; text-align:center; border-top:1px solid #30363d; padding-top:1rem;">
  <p>© 2025 TonNom — Projet Lookup GitHub</p>
  <p>Nous respectons pleinement les <a href="https://docs.github.com/en/site-policy/github-terms/github-terms-of-service" target="_blank" rel="noopener noreferrer" style="color:#58a6ff; text-decoration:none;">règles et conditions d'utilisation de GitHub</a>.</p>
</footer>

</body>
</html>
