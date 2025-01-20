# Live Coding Tests

Este documento incluye las instrucciones para las dos pruebas de live coding diseñadas para evaluar candidatos a desarrolladores web full-stack junior. Cada prueba tiene una duración de 1 hora y está estructurada para evaluar habilidades técnicas, resolución de problemas, comunicación y gestión del tiempo.

---

## Prueba 1: Sistema de Gestión de Tareas

### **Tiempo Total**
1 hora

### **Descripción**
Construir un sistema básico de gestión de tareas con una API REST y un frontend que interactúe con la API.

### **Aspectos a Evaluar**
1. **Habilidad técnica**: 
   - Implementación funcional de los endpoints.
   - Creación de un frontend interactivo.
   - Buenas prácticas básicas de código.
2. **Resolución de problemas**: 
   - Capacidad para identificar y solucionar errores.
   - Implementar soluciones simples y funcionales.
3. **Comunicación**: 
   - Explicación clara de las decisiones tomadas.
   - Capacidad para hacer preguntas relevantes.
4. **Gestión del tiempo**: 
   - Priorización de las funcionalidades obligatorias.

### **Funcionalidades Obligatorias**
#### Backend:
- Crear una API REST con **Node.js** (Express):
  - `POST /tasks`: Crear una tarea con los campos `title` (string) y `completed` (boolean, false por defecto).
  - `PATCH /tasks/:id`: Marcar una tarea como completada.
  - `GET /tasks`: Obtener todas las tareas.

#### Frontend:
- Crear una interfaz web que permita:
  - Agregar tareas usando un formulario.
  - Mostrar una lista de tareas con:
    - El título de cada tarea.
    - Un botón para marcar una tarea como completada.
  - Visualizar un estilo diferente para las tareas completadas (e.g., texto tachado o diferente color).

### **Funcionalidades Nice to Have**
1. Persistencia de datos (e.g., usar un archivo JSON en lugar de almacenamiento en memoria).
2. Validaciones adicionales en el backend (e.g., evitar títulos vacíos).
3. Diseño atractivo en el frontend (uso de CSS o frameworks como Tailwind).
4. Gestión de errores en el frontend (mostrar mensajes de error al usuario).

---
