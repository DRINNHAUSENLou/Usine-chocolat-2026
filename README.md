<h1 align="center">Usine Chocolat</h1>

<p align="center">
Usine Chocolat est une plateforme intégrée de gestion d'usine développée avec <strong>Laravel</strong>, reliée à une base de données <strong>MySQL</strong>, permettant de gérer et suivre tous les aspects de la production de chocolat.

Créée dans le cadre d'un projet de <strong>portes ouvertes</strong> en partenariat avec une filière de l'IUT spécialisée dans la <strong>qualité et production de vrais chocolat</strong>, cette application propose une <strong>interface mobile intuitive pour les visiteurs</strong> et une <strong>interface desktop complète pour les agents de la chaîne de production</strong> gérant les commandes, stocks et objectifs.

Le site intègre un système d'authentification sécurisé, une gestion hiérarchisée des équipes et postes, et une organisation complète : <strong>Équipes</strong> organisées par <strong>Postes</strong>, gestion des <strong>Commandes</strong> déclinées en <strong>Étapes</strong>, suivi des <strong>Stocks</strong> et <strong>Objectifs</strong> de production.
</p>


<h2>Actions à faire pour mettre en place le projet</h2>

<ul>
  <li>
    <strong>Cloner le dépôt :</strong><br>
    <pre><code>git clone https://github.com/DRINNHAUSENLou/sae501-2.git
cd sae501-2</code></pre>
  </li>

  <li>
    <strong>Installer les dépendances PHP et Node :</strong><br>
    <pre><code>composer install
npm install</code></pre>
  </li>

  <li>
    <strong>Créer le fichier .env et générer la clé de l'application :</strong><br>
    <pre><code>cp .env.example .env
php artisan key:generate</code></pre>
  </li>

  <li>
    <strong>Créer la base de données :</strong> <br>
    Créer une base nommée <strong>usine_chocolat</strong> dans phpMyAdmin ou via MySQL.
  </li>

  <li>
    <strong>Lancer les migrations et compiler les assets :</strong><br>
    <pre><code>php artisan migrate
npm run build</code></pre>
  </li>

  <li>
    <strong>Démarrer le serveur local :</strong><br>
    <pre><code>php artisan serve</code></pre>
  </li>

  <li>
    <strong>Accéder à l'application :</strong><br>
    <a href="http://localhost:8000">http://localhost:8000</a>
  </li>
</ul>

<h3 align="left">Langages et Outils :</h3>
<p align="left">
  <a href="https://laravel.com" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/laravel/laravel-plain.svg" alt="laravel" width="40" height="40"/>
  </a>
  <a href="https://www.php.net" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/php/php-original.svg" alt="php" width="40" height="40"/>
  </a>
  <a href="https://www.mysql.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/>
  </a>
  <a href="https://vuejs.org/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vuejs/vuejs-original-wordmark.svg" alt="vuejs" width="40" height="40"/>
  </a>
  <a href="https://tailwindcss.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-plain.svg" alt="tailwindcss" width="40" height="40"/>
  </a>
  <a href="https://www.javascript.com/" target="_blank" rel="noreferrer">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/>
  </a>
</p>
