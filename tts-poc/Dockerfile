# Utilizamos una imagen base de NGINX
FROM nginx

# Copiamos los archivos HTML, CSS y JS a la carpeta predeterminada de NGINX
COPY index.html /usr/share/nginx/html/
COPY style.css /usr/share/nginx/html/
COPY script.js /usr/share/nginx/html/
COPY img/ /usr/share/nginx/html/img/

# Exponemos el puerto 80 para que pueda ser accedido desde el exterior
EXPOSE 80
