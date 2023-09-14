## Preguntas

- ¿Cómo se inicializa un repositorio en Git?


Dandole "git bash here" en una carpeta y el "git init" en la terminal para inciar el repositorio.


- ¿Cómo creas un repositorio en GitHub?

Abriendo la pagina de github, entras a tu cuenta te vas a tus repositorios y te aparecera un boton de color verde que te da la opcion de crear un nuevo repositorio.

- ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?

Una ves que haces el commit, usas el comando "git branch -M main" para asegurarte que estas en la rama principal, despues usas "git remote add origin https://github.com/usuario/repositorio.git" para que los cambios que hagas en visual se suban correctamente en el repositorio que creaste y despues utilizas "git push -u origin main" para que se sincronice con tu repositorio de github.

```
git branch -M main
git remote add origin https://github.com/usuario/repositorio.git
git push -u origin main
```

- ¿Cuál es el flujo básico de trabajo en Git y GitHub?

Es usar todos los comandos para guardar los cambios, cargar los cambios y depues subirlos a tu repositorio de github.