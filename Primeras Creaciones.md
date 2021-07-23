# Primeras Creaciones 

En esta sesión se realizaron las primeras creaciónes en docker y se habló de varios temas 



# Parte Práctica
**Mi primer DockerFile**

Pasos para crear mi primer docker 
**1.** Crear carpeta con el comando 
> mkdir mi-primer-dockerfile

**2.** Entramos a la carpeta 

**3.** Entramos a editar el dockerfile con vim
> vim Dockerfile

Cuando estemos adentro copiamos lo siguiente:
> FROM nginx
> COPY static-html-directory /usr/share/nginx/html

para alojar contenido estático simple

**4.** Creamos nueva carpeta llamada static-html-directory
> mkdir static-html-directory

**5.** Entramos en ella y abrimos el documento index.html

> cd static-html-directory
> vim index.html

Escribimos algo que quisieramos mostrar en la pantalla de nuestro navegador, para esta práctica escribi: 
```Prueba para el curso de Docker del semillero de Fedesoft```


# Crear Imagen

