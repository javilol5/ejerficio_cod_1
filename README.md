Pasos realizados
1. Creación del repositorio

El desarrollador líder creó este repositorio en GitHub a partir de un ejercicio realizado en clase.

2. Creación del issue

El desarrollador líder creó un issue describiendo la tarea que debía realizar el colaborador.

3. Clonado del repositorio

El colaborador clonó el repositorio en su equipo local usando:

git clone <URL_DEL_REPOSITORIO>

4. Creación de una rama propia

El colaborador creó y trabajó únicamente en su rama, sin modificar la rama main:

git checkout -b nombre-rama-colaborador

5. Desarrollo y commits

El colaborador realizó los cambios solicitados y los guardó mediante commits:

git add .
git commit -m "Descripción de los cambios realizados"

6. Envío de cambios al repositorio remoto

El colaborador subió su rama al repositorio remoto:

git push origin nombre-rama-colaborador

7. Pull Request

El colaborador creó un Pull Request desde su rama hacia main para solicitar la mezcla de los cambios.

8. Revisión de código

Ambos desarrolladores mantuvieron un diálogo en el chat del Pull Request para revisar el código y proponer mejoras si era necesario.

9. Fusión de la rama

Tras la revisión, el desarrollador líder realizó el merge del Pull Request a la rama main.

10. Cierre del issue

Una vez completada la tarea, el colaborador cerró el issue asociado.

11. Actualización de repositorios locales

Para que ambos desarrolladores tengan todos los cambios en local, se utilizó:

git fetch
git pull
