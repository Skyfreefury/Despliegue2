# despliegue2

Web 2 del examen de despliegue: **consulta vecinal de Benimaclet**, encuesta ficticia por pasos con resultados.
Es un único `index.html` estático, sin compilación. La web 1 está en el repo `despliegue`.

```bash
sudo git clone https://github.com/Skyfreefury/despliegue2.git /var/www/web2
sudo chown -R www-data:www-data /var/www/web2
```

Nginx la sirve en el puerto 8082 con `root /var/www/web2;`.
