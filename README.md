# Como Usar y/o Gestionar Git en un repositorio

Para manejar git necesitamos seguir estos comandos, asi como tenerlo instalado de manera global en nuestro equipo.

1. **Inicializar nuestro repositorio con>**:

   ```sh
   git init
   ```

2. **Agregar archivos a nuestro repositorio con>**:

   ```sh
   git add .
   ```

3. **Agregar un commit o comentario para confirmar nuestros cambios con>**:

   ```sh
   git commit -m "Initial commit"
   ```

4. **Crear una rama para agregar nuestras caracteristicas**:

   ```sh
   git checkout -b feature-branch
   ```

5. **Unir nuestra rama de la nueva caracteristica con la rama principal**:
   ```sh
   git checkout main
   git merge feature-branch
   ```
