# servMNC.


## Instalación.

En la carpeta instalación encontrarás todo lo necesario para ejecutar el servidor de forma local.

### Java.

Comenzamos instalando los archivos *java* y *jdk16* en el caso de que no los tengamos instalados.
Tras instalarlo abrimos una **CMD** y ejecutamos `java --version` y obtendreis algo parecido a esta imagen:

![image](https://user-images.githubusercontent.com/57295165/121800211-c88b4900-cc30-11eb-9f80-1411a64100c4.png)

#### Añadir al path.

**Nota: en la carpeta instalación hay un tutorial en Aniadir al path.**

Para el correcto funcionamiento de java debemos de añadir al path de windows java, para ello vamos a escribir en el buscador de windows
**variables** y pulsamos intro, ahora nos vamos a la parte inferior de la ventana y pulsamos **Variables de entorno..**, en la nueva ventana en el cuadro inferior
nos vamos a la línea *path* y pulsamos sobre **editar**. 

En una de las líneas en blanco que nos aparece pulsamos en ella y despues en **Examinar**. Ahora nos vamos a la ruta de instalación de java
suele ser `C:\Program Files\Java` o `C:\Program Files (x86)\Java` una vez en esta carpeta veremos los paquetes de java instalado y entramos a una hasta la carpeta bin. Pulsamos aceptar para guardar la ruta. Debe de quedar algo así: ``C:\Program Files (x86)\Java\jre1.8.0_291\bin``.

### Git.

Para poder descargar y acutalizar este repositorio es indispensable tener git instalado, en la carpeta instalación hay un enlace para descargarlo. Seguimos el típico proceso de instalación.

Una vez hecho en el buscador de windows escribimos *git bash*.

![image](https://user-images.githubusercontent.com/57295165/121800518-b7dbd280-cc32-11eb-88b8-d6acdad1569e.png)

Se nos abrira un terminal parecido a CMD pero mejor.

Ahora escribimos estos comandos para que git nos "identifique":

``git config --global user.name "TU NOMBRE"``

``git config --global user.email "TU CORREO"``

Tras ello ya nos podemos descargar el repositorio ejecutando: 

``git clone https://github.com/Davavico22/servMNC.git``

### Ejecución del servidor.

Para ejecutar el servidor tenemos que abrir una terminal en el directorio ``ServidorMinecraft/server/``:

![image](https://user-images.githubusercontent.com/57295165/121800711-b959ca80-cc33-11eb-8243-3b37c995fb93.png)

Una vez que se nos abre escribirmos ``java -jar server.jar``.



