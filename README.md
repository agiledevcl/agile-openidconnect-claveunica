# Agile Conector Clave Única OpenID Connect
Ejemplo de conexión a Clave Única utilizando OpenID Connect 1.0 y las librerías de MITRE

## Prerrequisitos
Para poder utilizar este ejemplo debes agregar una aplicación en la [consola para desarrolladores](https://www.claveunica.cl/consola) de Clave Única y establecer como `REDIRECT_URI` `<hostname>/openidconnect-simple/return.jsp`. Así podrás obtener el `CLIENT_ID` y `CLIENT_SECRET`.

## Instalación
Antes de comenzar debes editar el archivo `src/main/webapp/request.jsp` y añadir tu `CLIENT_ID` y `CLIENT_SECRET`.

Para la construcción de este ejemplo se requiere tener instalado [maven](http://maven.apache.org/). 
Finalmente ejecutar ``mvn clean install``.
