<p align="center">
  <img src="https://i.ibb.co/yBXXfC39/1753994935738.png" alt="Lookup GitHub Banner" width="100%" />
</p>

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
<pre style="background:#f6f8fa; padding:1rem; border-radius:6px;">
<code>git clone https://github.com/ton-utilisateur/lookup-github.git
cd lookup-github
pip install -r requirements.txt
</code>
</pre>

<h2>Utilisation</h2>
<p>Lance le script et entre le nom d’utilisateur GitHub :</p>
<pre style="background:#f6f8fa; padding:1rem; border-radius:6px;">
<code>python main.py
</code>
</pre>
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

<footer style="margin-top:2rem; font-size:0.85rem; color:#666;">
  <p>© 2025 TonNom — Projet Lookup GitHub</p>
  <p>Nous respectons pleinement les <a href="https://docs.github.com/en/site-policy/github-terms/github-terms-of-service" target="_blank" style="color:#0366d6; text-decoration:none;">règles et conditions d'utilisation de GitHub</a>.</p>
</footer>
