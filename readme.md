# Sistema de Gestión Empresarial

## Descripción del proyecto

Aplicación web alojada en Heroku que implementa un sistema de fidelización para pacientes de un centro médico, proporcionando acceso exclusivo a beneficios mediante registro de usuario.

Las tecnologías y herramientas ocupadas son las siguientes:
- Django
- PostgreSQL
- HTML

## Consideraciones

-  El sistema debe permitir registrar nuevos participantes.
-  Se debe crear una vista para que los participantes puedan iniciar sesión con su correo y contraseña.
-  Luego de iniciar la sesión, los participantes deberán poder modificar sus datos, exceptuando el correo electrónico y su foto. Esta vista esta protegida con csrf_token y los datos que se utilicen en la plantilla son extraídos del token.
-  La vista del administrador debe mostrar los participantes registrados y permitir aprobarlos para cambiar su estado.

## Comenzando 🚀

_Estas instrucciones te permitirán obtener una copia del proyecto en funcionamiento en tu máquina local para propósitos de desarrollo y pruebas._

Mira **Deployment** para conocer como desplegar el proyecto.


### Pre-requisitos 📋

_Que cosas necesitas para instalar el software y como instalarlas_

```
Visual Studio Code, PyCharm
```
```
Python 3
```
```
Git, Github
```
```
variables de entorno para python
```
### Instalación 🔧

```
Importar proyecto al IDE de preferencia para ejecutar.
```

## Deployment 📦

Realizar un fork o clon del proyecto, importar al IDE de preferencia, para ejecutar en consola realizar el build (empaquetado) de la aplicación.


```

## Construido con 🛠️

* [Python](https://www.python.org/downloads/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Git](https://git-scm.com/)
* [GitHub](https://github.com/)


## Versionado 📌

## Autores ✒️

https://github.com/victorpenafiel

## Licencia 📄

Ningún derecho reservado.  [Creative Commons Atribución/Reconocimiento 4.0 ](https://creativecommons.org/licenses/by/4.0/deed.es).

Este proyecto está bajo la Licencia - mira el archivo [LICENSE.md](LICENSE.md) para detalles