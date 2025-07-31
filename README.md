<!DOCTYPE html>
<html lang="fr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Lookup GitHub - README</title>
<style>
  body {
    font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
    background: #0d1117;
    color: #c9d1d9;
    margin: 2rem auto;
    max-width: 720px;
    line-height: 1.6;
    padding: 0 1rem;
  }
  h1, h2 {
    color: #58a6ff;
    border-bottom: 2px solid #30363d;
    padding-bottom: 0.3rem;
  }
  code {
    background: #161b22;
    padding: 0.2rem 0.4rem;
    border-radius: 4px;
    font-family: "Fira Mono", monospace, monospace;
  }
  pre {
    background: #161b22;
    padding: 1rem;
    border-radius: 8px;
    overflow-x: auto;
    margin: 1rem 0;
  }
  a {
    color: #58a6ff;
    text-decoration: none;
  }
  a:hover {
    text-decoration: underline;
  }
  ul {
    margin-left: 1.2rem;
  }
  footer {
    margin-top: 3rem;
    font-size: 0.9rem;
    color: #8b949e;
    text-align: center;
  }
</style>
</head>
<body>

<h1>Lookup GitHub</h1>

<p>Un outil simple pour récupérer et sauvegarder les données publiques d’un utilisateur GitHub, en local et avec résumé console.</p>

<h2>Fonctionnalités</h2>
<ul>
  <li>Infos de profil (nom, bio, followers, repos...)</li>
  <li>Détails des dépôts et gists publics</li>
  <li>Liste complète des followers et following</li>
  <li>Historique des événements publics</li>
  <li>Export automatique dans des fichiers texte</li>
  <li>Affichage résumé stylé dans la console</li>
</ul>

<h2>Installation</h2>
<pre><code>git clone https://github.com/ton-utilisateur/lookup-github.git
cd lookup-github
pip install -r requirements.txt
</code></pre>

<h2>Utilisation</h2>
<p>Lance le script et entre le nom d’utilisateur GitHub :</p>
<pre><code>python main.py
</code></pre>
<p>Les fichiers seront sauvegardés dans <code>output/&lt;username&gt;/</code></p>

<h2>Fichiers créés</h2>
<ul>
  <li><code>info.txt</code> — résumé général</li>
  <li><code>followers.txt</code> et <code>following.txt</code> — listes d’abonnés</li>
  <li><code>repos.txt</code> — détails des dépôts</li>
  <li><code>gists.txt</code> — gists publics</li>
  <li><code>events.txt</code> — historique des événements</li>
</ul>

<h2>Limitations</h2>
<ul>
  <li>API GitHub non authentifiée → limite d’appels par heure</li>
  <li>Données privées non accessibles</li>
  <li>Connexion internet nécessaire</li>
</ul>

<footer>© 2025 TonNom — Projet Lookup GitHub</footer>

</body>
</html>
