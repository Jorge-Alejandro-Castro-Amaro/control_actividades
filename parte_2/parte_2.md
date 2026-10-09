1. Flujo colaborativo

Supón que quieres colaborar con el repositorio de otro desarrollador. Ordena y explica los siguientes elementos:
Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y Modificar archivos. Agrega cualquier
operación que consideres necesaria.

1.- Realizar un fork en el repositorio del usuario (el usuario te debe de compartir su URL de su repositorio para realizar esta accion.)

2.- Clonas su repositorio con git clone "URL REPO"

3.- Agregas una rama de apoyo o colaboracion con el comando "git switch -c nomb-rama"

4.- Branch verificas si vas a subir el commit en esa rama que creaste.

5.- git commit realizas el commit con el cambio o implementacion.

6.- Push Realizas un git push -u origin nomb-rama para subir los cambios a github.

7.- Pull request para enviar los datos de la rama.

8.- Review Se revisan los cambios.

9.- Merge se aceptan los cambios y se integran al repositorio original.

10.- Pull git pull para sincronizar los documentos a la estructura principal.

2. Fork y Clone

Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”. Indica si es correcta

R: Falso.

y explica la diferencia entre Fork y Clone.

Diferencia:

Fork: Se podria decir que se crea una copia del repositorio en github.

Clone: Este nos permite clonar el repositorio con la URL del proyecto Forkeado permitiendonos ejecutarlo desde la terminal con el comando git clone "URL"

3. Pull Request

Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: ¿los cambios ya forman parte
del repositorio original? ¿Qué debe ocurrir para incorporarlos?

Basicamente para que formen parte se deben aceptar mediante un merge si los cambios o implementacion que realizo el usuario son correctos se realiza el merge despues de esto el lider realiza un git pull para sincronizar los archivos en su visual studio

4. Request Changes

El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear
otro Pull Request y qué ocurre cuando realizas nuevamente push.

Cuando el lider realiza un request changes te devuelve el pull request, para esto modificas el archivo que te solicito modificar y realizas los pasos de git add . -> git commit -m "" -> git push -> con esto se actualiza automaticamente el pull request despues el lider verifica nuevamente los cambios y si esta bien realiza el merge.

5. Merge y repositorio local

Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no
contiene los cambios. Explica por qué sucede y qué operación debe realizarse.

R: Se necesita realizar un git pull desde vs para sincronizar la informacion.

6. Sync Fork

Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué herramienta
utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull.
Registra este cambio en un cuarto commit con un mensaje descriptivo y súbelo a github.


R:

Cuando tu fork está desactualizado respecto al repositorio original, la herramienta es:

git remote add upstream URL_REPO_ORIGINAL  
y luego:
git pull upstream master (o la rama principal, que puede ser main).

Sync Fork (en GitHub web):

Es una opción que sincroniza tu fork remoto (el que está en tu cuenta de GitHub) con el repositorio original.

No toca tu copia local, solo actualiza el fork en la nube.

git pull:

Se usa en tu entorno local (VS Code, Visual Studio, etc.).

Trae los cambios desde un remoto (puede ser origin o upstream) hacia tu repositorio local.

Es lo que realmente actualiza tu carpeta de trabajo.
