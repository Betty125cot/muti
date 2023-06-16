# muti
RewriteEngine on
RewriteCond %{SERVER_PORT} 80
RewriteRule ^(.*)$ https://Betty125.github.io/muti/index.html$1 [R,L]
