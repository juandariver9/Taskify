---

# Taskify

**Taskify** es una aplicación de gestión de tareas diaria desarrollada en Python. Permite a los usuarios organizar y realizar un seguimiento eficiente de sus pendientes, integrando funcionalidad tanto de persistencia de datos como de manejo de excepciones para asegurar una experiencia robusta.

## Características principales

1. **Agregar tareas**  
   Permite al usuario crear nuevas tareas con un título y una descripción.

2. **Listar tareas**  
   Muestra todas las tareas agregadas con su estado actual (pendiente o completada).

3. **Marcar tareas como completadas**  
   Ofrece la opción de actualizar el estado de una tarea a "completada".

4. **Eliminar tareas**  
   Elimina tareas completadas según las necesidades del usuario.

5. **Guardar y cargar tareas**  
   Exporta las tareas a un archivo para su almacenamiento o importa tareas desde un archivo existente.

6. **Interfaz flexible**  
   Disponible en versión de línea de comandos. Posibilidad de expandirla a una interfaz gráfica en el futuro.

## Requisitos técnicos

- Uso de estructuras de datos como listas y diccionarios.
- Manejo de excepciones para evitar cierres inesperados de la aplicación.
- Importación y exportación de tareas usando el módulo estándar `json`.
- Persistencia de datos mediante una base de datos SQL, idealmente utilizando SQLAlchemy.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu-usuario/taskify.git
   cd taskify
   ```

2. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```

3. Configura la base de datos (si es necesario):
   ```bash
   python setup_db.py
   ```

4. ¡Ejecuta la aplicación!
   ```bash
   python taskify.py
   ```

## Contribuciones

¡Contribuciones, sugerencias y reportes de errores son bienvenidos! Si deseas colaborar, crea un *fork* del repositorio, realiza tus cambios y envía un *pull request*.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo `LICENSE` para más detalles.

