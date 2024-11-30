# PROYECTO DE PLATAFORMA DE PELICULAS

Este proyecto está desarrollado en Java 23 y consta de tres aplicaciones independientes que pueden ejecutarse desde la consola. Las aplicaciones están empaquetadas en tres archivos JAR separados, y cada uno cumple con una función específica dentro de la plataforma de películas.

## Estructura del Proyecto

El proyecto está dividido en tres aplicaciones principales:

1) **Cliente (Client):**  Esta es la aplicación principal para interactuar con la plataforma de películas. El cliente se encarga de la interacción del usuario y el envío de solicitudes al servidor.
2) **Servidor (Server):** El servidor maneja las peticiones recibidas del cliente y administra la base de datos de usuarios, películas, categorías y más.
3) **Persistencia (Persistence):** Esta aplicación se encarga de la gestión de los datos y su almacenamiento en archivos.
   
## Requisitos

* **Java 23:** El proyecto está desarrollado con la versión 23 de Java. Asegúrate de tener instalada esta versión o una versión compatible.
* **Archivos JAR:** El proyecto está empaquetado en tres archivos JAR independientes. Estos pueden ejecutarse en la consola utilizando el comando `java -jar.`

## Intrucciones de Ejecucion

1) **Ejecutar el servidor:** Antes de ejecutar cualquier otra aplicación, siempre debes ejecutar primero el Servidor. El servidor es el que inicia la comunicación con las otras aplicaciones. Para ejecutarlo, abre una terminal y usa el siguiente comando:
   
   `java -jar ruta/del/servidor.jar`

2) **Ejecutar el Cliente/Administrador:** Una vez que el servidor esté en funcionamiento, puedes iniciar el servidor. Para ejecutar el cliente, usa el siguiente comando en otra terminal: 

   `java -jar ruta/de/la/aplicacion.jar`  

## Archivo `Config.properties`

El archivo `Config.properties` debe encontrarse en la carpeta data/files/ dentro del directorio donde se ejecuta el JAR. Este archivo contiene la configuración y las propiedades necesarias para que las aplicaciones funcionen correctamente.

## Codigo Fuente

Además de los archivos JAR, también se proporciona el código fuente completo de las tres aplicaciones. El código fuente está disponible dentro de la carpeta del proyecto. 