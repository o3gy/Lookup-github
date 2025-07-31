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
  header {
    display: flex;
    align-items: center;
    gap: 0.6rem;
    margin-bottom: 1.5rem;
  }
  h1 {
    color: #58a6ff;
    font-weight: 700;
    font-size: 2.4rem;
    margin: 0;
  }
  svg.github-logo {
    width: 40px;
    height: 40px;
    fill: #58a6ff;
  }
  h2 {
    color: #58a6ff;
    border-bottom: 2px solid #30363d;
    padding-bottom: 0.3rem;
    margin-top: 2rem;
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
    font-size: 0.85rem;
    color: #8b949e;
    text-align: center;
    border-top: 1px solid #30363d;
    padding-top: 1rem;
  }
</style>
</head>
<body>

<header>
  <svg class="github-logo" viewBox="0 0 24 24" aria-hidden="true" focusable="false" >
    <path d="M12 0.296c-6.627 0-12 5.373-12 12 0 5.303 3.438 9.8 8.205 11.387 
             0.6 0.111 0.82-0.26 0.82-0.577 0-0.285-0.011-1.04-0.017-2.04-3.338 
             0.724-4.042-1.61-4.042-1.61-0.546-1.387-1.333-1.757-1.333-1.757-1.09-0.745 
             0.083-0.73 0.083-0.73 1.205 0.084 1.84 1.236 1.84 1.236 1.07 1.834 2.809 
             1.304 3.495 0.997 0.108-0.775 0.418-1.305 0.76-1.605-2.665-0.3-5.466-1.335-5.466-5.93 
             0-1.31 0.468-2.381 1.236-3.221-0.124-0.303-0.536-1.523 0.117-3.176 0 0 1.008-0.322 
             3.301 1.23 0.957-0.266 1.984-0.399 3.003-0.404 1.018 0.005 2.045 0.138 3.003 0.404 
             2.291-1.552 3.297-1.23 3.297-1.23 0.655 1.653 0.243 2.873 0.12 3.176 0.77 0.84 
             1.235 1.911 1.235 3.221 0 4.609-2.807 5.625-5.479 5.921 0.43 0.371 0.823 1.102 0.823 2.222 
             0 1.606-0.014 2.898-0.014 3.293 0 0.319 0.216 0.694 0.825 0.576 4.765-1.59 8.199-6.086 
             8.199-11.386 0-6.627-5.373-12-12-12z"/>
  </svg>
  <h1>Lookup GitHub</h1>
</header>

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

<footer>
  <p>© 2025 TonNom — Projet Lookup GitHub</p>
  <p>Nous respectons pleinement les <a href="https://docs.github.com/en/site-policy/github-terms/github-terms-of-service" target="_blank" rel="noopener noreferrer">règles et conditions d'utilisation de GitHub</a>.</p>
</footer>

</body>
</html>
