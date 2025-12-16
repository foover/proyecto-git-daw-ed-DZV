# Mini Proyecto Git

Este proyecto sirve como práctica de manejo de ramas y control de versiones con Git.

## Pasos realizados

1. **Creación de la carpeta del proyecto**
   - Se creó la carpeta `mini-proyecto-git` dentro de `Documents`.
   - Dentro de ella, se creó la carpeta `src` para el código Java.

2. **Inicialización del repositorio Git**
   - Se ejecutó `git init` dentro de `mini-proyecto-git` para inicializar un repositorio vacío.

3. **Creación y commit del archivo Java**
   - Se creó el archivo `Main.java` dentro de `src`.
   - Se añadió al staging con `git add Main.java`.
   - Se realizó el primer commit con:
     ```
     git commit -m "Se ha creado el archivo Main.java y se ha modificado su contenido"
     ```

4. **Creación de ramas**
   - Se cambió de rama y se renombraron según la práctica:
     - `feature-java-utils`
     - `feature-web-layout`
     - `hotfix-readme`
   - Para crear y cambiar de rama se utilizó:
     ```
     git checkout -b nombre_rama
     ```

5. **Creación de archivos para la rama web**
   - En la rama `feature-web-layout` se creó la carpeta `web`.
   - Se añadieron los archivos `index.html` y `styles.css` dentro de `web`.
   - Se añadieron al staging y se hizo commit con:
     ```
     git add .
     git commit -m "Se ha añadido el index.html y su hoja de estilos correspondiente, ambos han sido modificados"
     ```

6. **Modificaciones en ramas**
   - Se realizaron cambios en los archivos según la rama activa.
   - Cada cambio relevante se añadió y se confirmó mediante commit.

7. **Creación y edición de README**
   - En la rama `hotfix-readme` se creó el archivo `README.md` para documentar la práctica.

## Observaciones

- Se ha trabajado principalmente con Git Bash.
- Se han practicado comandos como `git status`, `git add`, `git commit`, `git branch` y `git checkout`.
- Se ha manejado la creación, modificación y eliminación de archivos en distintas ramas para simular un flujo de trabajo real.
