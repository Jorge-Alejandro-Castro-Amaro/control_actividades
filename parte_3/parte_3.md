1. Analiza
1 git status
2 git add README.md
3 git commit -m "Actualiza documentación"
4 git push
5 Explica qué ocurre en cada instrucción.

R1: Valida el estado actual de los archivos.
R2: Añade el archivo README.md para subir.
R3: Se crea el commit y se le agrega el nombre para identificar el cambio.
R4: Sube los archivos al repositorio. 

2. Identifica qué falta
Caso A
Modificar archivo
↓
git add .
↓
¿?
↓
git push
Indica qué operación falta y explica su función.

R: 
1.- git commit -m "nombre del commit" (Permite realizar el commit y agregarle un nombre que lo identifique el cambio)
  

-------
Caso B
Repositorio GitHub
↓
¿?
↓
Repositorio local
Indica qué operación utilizarías y explica por qué.

R: git pull origin main para sincronizar los archivos en mi vs.


------
Caso C
Repositorio remoto actualizado
↓
¿?
↓
Repositorio local actualizado

R: Git pull