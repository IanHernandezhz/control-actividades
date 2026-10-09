# Parte 2: Comprension del flujo colaborativo
## 1. Flujo colaborativo
### Planteamiento
Supon que quieres colaborar con el repositorio de otro desarrollador. Ordena y explica los siguientes elementos: Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y Modificar archivos. Agrega cualquier operacion que consideres necesaria.
### Explicacion
El orden logico del flujo de trabajo para colaborar en un proyecto de codigo abierto o ajeno es el siguiente:

1. Fork: Crea una copia remota del repositorio original directamente en tu propia cuenta de GitHub.
2. Clone: Descarga una copia del repositorio de tu cuenta de GitHub a tu equipo local para poder trabajar en el.
3. Branch: Crea una rama secundaria para aislar los cambios del codigo principal el main.
4. Modificar los archivos: Realizas los cambios, correcciones o nuevas caracterasticas directamente en el codigo dentro de tu entorno local.
5. Commit: Guardas una instantanea local de los cambios realizados en el historial de Git, acompañados de un mensaje explicativo.
6. Push: Subes la rama local con tus nuevos commits a tu repositorio remoto en GitHub (tu Fork).
7. Pull Request: Envias una solicitud al dueño del repositorio original proponiendo la integracion de tus cambios.
8. Review: El propietario o los mantenedores del proyecto original revisan tu codigo, hacen observaciones, pruebas o solicitan ajustes.
9. Merge: Una vez aprobados los cambios, el mantenedor del proyecto fusiona la rama de tu Pull Request dentro de la rama principal del repositorio original.
## 2. Fork y Clone
### Planteamiento
Analiza la afirmacion:Clone crea una copia del proyecto dentro de mi cuenta de GitHub. Indica si es correcta y explica la diferencia entre Fork y Clone.
### Explicacion
Es incorreccto
Fork: Es una operacion que ocurre a nivel del servidor.Se encarga de duplicar un repositorio ajeno para crear una copia exacta dentro de la cuenta de github.
Clone: Es una operacion de Git que descarga una copia de un repositorio remoto a tu computadora.

Para copiar un proyecto a la cuenta de Git hub es el FORK y para descargarlo al equipo de trabajo es el CLONE 

## 3. Pull Request
### Planteamiento
Supon que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: los cambios ya forman parte del repositorio original? Que debe ocurrir para incorporarlos?

### Explicacion
No los cambios aun no forman parte del repositorio original. Los cambios solo existen en la computadora  y en la copia remota de tu propia cuenta de GitHub el Fork.
Para que se incorporen al repositorio original primero es.

1. Crear un Pull Request: Debes abrir una solicitud desde tu repositorio hacia la rama principal del repositorio original.
2. Revision El dueño o equipo encargado del repositorio original debe revisar el codigo para comprobar que cumpla con los estandares, pase las pruebas automaticas y no introduzca errores.
3. Aprobacion y Merge: El dueño del proyecto debe aceptar la propuesta y realizar la accion de Merge. Una vez ejecutada la fusion, los cambios formaron parte oficialmente del proyecto principal.

## 4. Request Changes
### Planteamiento
El propietario revisa tu Pull Request y selecciona Request Changes. Explica que debes hacer, si necesitas crear otro Pull Request y que ocurre cuando realizas nuevamente push.

### Explicacion
Que hacer: Debes leer las observaciones y retroalimentacion dejadas por el propietario en el Pull Request, realizar los ajustes o correcciones solicitadas en tu codigo dentro de la misma rama de tu maquina local, y guardar los cambios con nuevos commit.
Necesitas crear otro Pull Request?:No es necesario abrir un nuevo Pull Request.
Que ocurre al hacer el push? Cuando ejecutas git push en la misma rama desde tu entorno local hacia tu Fork en GitHub, los nuevos commits se añaden al Pull Request existente, actualizando todo 

## 5. Merge y repositorio local
### Planteamiento
Un Pull Request fue aceptado y se realizo Merge en GitHub. Sin embargo, el repositorio local del propietario no contiene los cambios. Explica por que sucede y que operacion debe realizarse. Poeque el merge no se ejecuto bien, y solo la copia remota tiene los cambios integrados y hace que no sincorinzen de forma autoamtica los cambios . Para que se hagana los cambios debe de ir a la main y hacer un git pull 

## 6. Sync Fork
### Planteamiento
Tu Fork fue creado varios dias atras y el repositorio original recibio nuevos commits. Explica que herramienta utilizaras, que repositorio se actualiza y que diferencia existe entre Sync Fork y git pull.
### Explicacion
 Se utiliza la opcion SYNC FORK directamente desde la platafroma de GitHub .
Que repositorio se actualiza:La opcion Sync Fork actualiza la copia remota del Fork en GitHub, 
Diferencia entre Sync Fork y git pull:
Sync Fork:Sincroniza la distancia entre dos repositorios remotos en GitHub 
git pull: Sincroniza un repositorio remoto con tu repositorio local