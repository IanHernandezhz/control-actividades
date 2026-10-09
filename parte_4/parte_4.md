# Parte 4: Conceptos

## 1. Diferencia entre Git y GitHub
Git: Es un sistema de control de versiones que se ejecuta localmente en tu computadora para rastrear los cambios en el codigo.
GitHub: Es una plataforma en la nube que aloja repositorios de git y facilita el trabajo colaborativo en linea.

## 2. Para que sirve .gitignore
Es un archivo de configuracion que le indica a git cuales archivos o carpetas debe ignorar y no incluir en el control de versiones 

## 3. Por que .venv no debe almacenarse en GitHub
Porque es un entorno virtual local que contiene archivos pesados y especificos del sistema operativo de cada usuario. Se puede recrear facilmente en cualquier otra maquina usando el archivo
equirements.txt\.

## 4. Para que sirve requirements.txt
Es un archivo de texto que lista todas las librerias y dependencias externas del proyecto junto con sus versiones para que otros desarrolladores puedan instalarlas facilmente.

## 5. Diferencia entre Stage, Commit y Push
git add: Prepara los archivos seleccionados para ser guardados.
git commit:Guarda la instantanea de los cambios preparados en el historial local.
git push:Envia los commits del historial local al repositorio remoto en GitHub.

## 6. Por que un repositorio puede tener varios commits antes de realizar un push
Porque git trabaja de forma independiente y desconectada localmente. Puedes registrar varios avances, correcciones o hitos individualmente en tu computadora y despues subir todo el historial junto a GitHub en una sola conexion.
