**Aplicación de Tareas**

Esta es una aplicación de tareas sencilla desarrollada con React. Permite a los usuarios agregar, completar y eliminar tareas, así como filtrar tareas según su estado de finalización.

**Características:**
- Agregar nuevas tareas
- Marcar tareas como completadas
- Eliminar tareas
- Filtrar tareas por todas, activas o completadas
- Borrar todas las tareas completadas

**Instalación:**
1. Clona el repositorio:
    ```bash
    git clone https://github.com/tu-usuario/todo-app.git
    cd todo-app
    ```

**Componentes:**

1. **App.js**: Es el componente principal de la aplicación. Maneja el estado de la lista de tareas y el filtro activo, además de contener las siguientes funciones:
    - `addTodo(title)`: Agrega una nueva tarea a la lista.
    - `handleSetComplete(id)`: Alterna el estado de completado de una tarea.
    - `handleDelete(id)`: Elimina una tarea de la lista.
    - `handleClearComplete()`: Borra todas las tareas completadas.
    - `showAllTodos()`: Muestra todas las tareas.
    - `showActiveTodos()`: Muestra solo las tareas activas.
    - `showCompletedTodos()`: Muestra solo las tareas completadas.

2. **TodoInput.jsx**: Renderiza un campo de entrada para que los usuarios escriban y agreguen nuevas tareas. Función:
    - `handleTodo(e)`: Agrega una nueva tarea al presionar la tecla Enter.

3. **TodoList.jsx**: Renderiza la lista de tareas y los filtros, utilizando las siguientes funciones pasadas desde App.js:
    - `handleSetComplete(id)`: Alterna el estado de completado de una tarea.
    - `handleDelete(id)`: Elimina una tarea.
    - `handleClearComplete()`: Borra todas las tareas completadas.
    - `showAllTodos()`: Muestra todas las tareas.
    - `showActiveTodos()`: Muestra solo las tareas activas.
    - `showCompletedTodos()`: Muestra solo las tareas completadas.

4. **Todo.jsx**: Renderiza una sola tarea, utilizando las siguientes funciones pasadas desde TodoList.jsx:
    - `handleSetComplete(id)`: Alterna el estado de completado de una tarea.
    - `handleDelete(id)`: Elimina una tarea.

5. **TodoFilters.jsx**: Renderiza los botones de filtro y el botón para borrar tareas completadas, utilizando las siguientes funciones pasadas desde TodoList.jsx:
    - `showAllTodos()`: Muestra todas las tareas.
    - `showActiveTodos()`: Muestra solo las tareas activas.
    - `showCompletedTodos()`: Muestra solo las tareas completadas.
    - `handleClearComplete()`: Borra todas las tareas completadas.

**Uso:**
1. Abre la aplicación en tu navegador.
2. Escribe una nueva tarea en el campo de entrada y presiona Enter para agregarla a la lista.
3. Haz clic en el círculo junto a una tarea para marcarla como completa o incompleta.
4. Haz clic en la "X" junto a una tarea para eliminarla.
5. Usa los botones de filtro para mostrar todas las tareas, solo las tareas activas o solo las tareas completadas.
6. Haz clic en "Borrar Completadas" para eliminar todas las tareas completadas de la lista.

**Contribuciones:**
Jhoan, sus compañeros, lo que aprendimos en clase y nuestro maestro Lizandro.

**Licencia:**
Este proyecto está licenciado bajo la Licencia de Cristo nuestro salvador, el que nos permitira pasar nuestros obstaculos y por ende, pasar la materia.
