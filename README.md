# Taller-Docker
Se crea repositorio del taller docker

## Parte 1
<div id="header" align="center">
    <img src="/img_taller/Imagen1.png" width="1000" />
   

</div>

#### **1.	Creación de cuenta de Github:** 
Se ingresa a la página oficial de Github y en la opción de Sign in se ingresan los datos (correo y password) para crear la sesión.
<img src="/img_taller/Imagen1_punto1.png" width="1000" />
<img src="/img_taller/Imagen2_punto1.png" width="1000" />

#### **2.	Creación de Repositorio en Github:**
a. Se procede a crear un repositorio con el nombre del Taller Docker, allí se guardará todos los documentos que se van a generar en el taller adicional este repositorio se va a clonar en el servidor AWS.
<img src="/img_taller/Imagen1_punto2.png" width="1000" />

#### Luego de crear el repositorio se realiza la clonación en el servidor siguiendo los siguientes pasos:
a.	En el servidor se ejecuta el comando ssh-keygen para que genere el par de llaves con el cual se va a conectar de manera segura al repositorio del Github.

b.	Luego abrimos el archivo id_rsa.pub, para copiar el hash y pegarlo en el repositorio como lo podemos ver en las siguientes imágenes
<img src="/img_taller/Imagen2_punto2.png" width="1000" />
c.	Luego se pega este hash en la pestaña de Setings y la opción SSH and GPG keys  se busca la pestaña de new SSH keys y allí se pega el hash que se copio del la llave generada por el servidor anteriormente y se le debe asignar un nombre como se muestra en las siguientes imágenes:
<img src="/img_taller/Imagen3_punto2.png" width="1000" />
<img src="/img_taller/Imagen4_punto2.png" width="1000" />
<img src="/img_taller/Imagen5_punto2.png" width="1000" />
<img src="/img_taller/Imagen6_punto2.png" width="1000" />
d.	Luego se debe crea una rama para el desarrollo con el nombre gh-pages:
<img src="/img_taller/Imagen7_punto2.png" width="1000" />
e.	Luego se procede a clonar el repositorio en el servidor con el comando git clone + la URL que se debe extraer del repositorio en la opción de <> code:
<img src="/img_taller/Imagen8_punto2.png" width="1000" />
<img src="/img_taller/Imagen9_punto2.png" width="1000" />
<img src="/img_taller/Imagen10_punto2.png" width="1000" />
f.	Se puede evidenciar que se clono exitosamente si revisamos las carpetas creadas o con el comando cd/Repositorios/Taller Docker  ls:

#### 3.	Creación del repositorio en DockerHub:
a.	Se ingresa a la pagina de Dockerhub  https://hub.docker.com/ y se ingresan los datos solicitados como se muestra en la siguiente imagen:
<img src="/img_taller/Imagen1_punto3.png" width="1000" />
b.	Se crea un repositorio:
<img src="/img_taller/Imagen2_punto3.png" width="1000" />
