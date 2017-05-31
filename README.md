### Example of run full stack lamp
Includes phpmyadmin, php-fpm, nginx, apache2-mpm, mailhog.

### How to run
Run as usual, inside folder with docker-compose.yml: <code>docker-compose up -d</code>

### Special info
<p>This example include php5-fpm, nginx(optional), apache2 mpm, mysql, mailhog, phpmyadmin.</p>
<p>You could view site info with nginx by link http://locahost:8005/info.php or by ip http://172.55.0.6/info.php</p>
<p>You could view site info with apache2 mpm by link http://locahost:8004/info.php or by ip http://172.55.0.5/info.php</p>
<p> Phpmyadmin is available under 172.55.0.3</p>
<p> Mailhog is available under 172.55.0.7:8025 </p>
<p> More details about avaialable ENV variables are inside images READMEs: </p>
<ul>
<li>https://github.com/a-kom/alpine-php_fpm</li>
<li>https://github.com/a-kom/alpine-nginx</li>
<li>https://github.com/a-kom/alpine-apache</li>
</ul>
