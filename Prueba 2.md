## Prueba 2: Sistema de Registro e Inicio de Sesión

### **Tiempo Total**
1 hora

### **Descripción**
Crear un sistema de autenticación básico que permita registrar usuarios, iniciar sesión y mostrar un perfil simple.

### **Aspectos a Evaluar**
1. **Habilidad técnica**: 
   - Implementación de lógica de registro e inicio de sesión.
   - Uso adecuado de herramientas para gestionar autenticación.
   - Buenas prácticas de seguridad básica.
2. **Resolución de problemas**: 
   - Identificar y resolver problemas comunes en autenticación.
   - Implementar validaciones funcionales.
3. **Comunicación**: 
   - Explicación de cómo se aborda la autenticación y la estructura de la solución.
   - Preguntas claras y relevantes si algo no está claro.
4. **Gestión del tiempo**: 
   - Priorización de los endpoints y funcionalidades obligatorias.

### **Funcionalidades Obligatorias**
#### Backend:
- Crear una API REST con **Node.js** (Express):
  - `POST /signup`: Registrar un usuario con los campos `username` (string) y `password` (string).
    - Validar que el `username` no esté repetido.
  - `POST /signin`: Verificar `username` y `password`.
    - Responder con un mensaje de éxito o error.
  - `GET /profile`: Retornar información del usuario autenticado (simular autenticación con un token básico).

#### Frontend:
- Crear una interfaz web que permita:
  - Un formulario de registro (campos: `username`, `password`).
  - Un formulario de inicio de sesión (campos: `username`, `password`).
  - Una vista de "perfil" que muestre información básica del usuario autenticado.

### **Funcionalidades Nice to Have**
1. Persistencia de usuarios (e.g., almacenar usuarios en un archivo JSON en lugar de memoria).
2. Hash de contraseñas en el backend (e.g., usando bcrypt).
3. Manejo de sesiones más realista (e.g., simulación de JWT o cookies).
4. Estado visual dinámico en el frontend:
   - Mensajes de error claros para fallos en registro o inicio de sesión.
   - Indicador de "usuario autenticado" (e.g., mostrar nombre en la barra superior).
5. Diseño atractivo en el frontend.

---

¡Buena suerte al aspirante! Estas pruebas están diseñadas para evaluar tanto habilidades técnicas como el enfoque para resolver problemas en tiempo limitado.