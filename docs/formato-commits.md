## 📌 Convención para Mensajes de Commits

Para mantener un historial de cambios claro, organizado y fácilmente trazable con las historias de usuario (HU) y el contexto del proyecto (Frontend, Backend o Documentación), seguimos la siguiente convención:

---

### Formato general del mensaje de commit:

tipo(contexto)(HU-id): descripción breve del cambio

- **tipo**: Describe el tipo de cambio realizado.
- **contexto**: Indica en qué parte del proyecto se hizo el cambio (`frontend`, `backend`, `docs`, etc.).
- **HU-id**: Opcional. Solo se incluye si el cambio está relacionado con una Historia de Usuario (HU).

---

### Tipos de commit permitidos:

| Tipo        | Uso                                                |
|-------------|----------------------------------------------------|
| **feat**    | Nueva funcionalidad.                               |
| **fix**     | Corrección de errores o bugs.                      |
| **refactor**| Cambios en el código que no afectan la funcionalidad (limpieza, optimización). |
| **style**   | Cambios de formato (espacios, indentación, etc.).  |
| **docs**    | Cambios o adiciones en la documentación.           |
| **test**    | Agregado o modificación de pruebas.                |
| **chore**   | Tareas de mantenimiento o configuración (sin afectar el código de producción). |

---

### Ejemplos de mensajes de commit:

- `feat(frontend)(HU-1): agregar formulario de registro de usuario`
- `fix(backend)(HU-5): corregir error al crear nuevas tareas`
- `refactor(backend): optimizar el servicio de autenticación`
- `style(frontend): ajustar estilos en el componente de login`
- `docs: actualizar guía de nomenclatura de ramas`
- `test(frontend): agregar pruebas unitarias para el módulo de tareas`
- `chore(backend): actualizar dependencias de NestJS`

---

### Reglas básicas:

- ✅ El **tipo** siempre en minúsculas.
- ✅ El **contexto** entre paréntesis: `frontend`, `backend` o `docs`.
- ✅ El **HU-id** solo si el cambio está relacionado con una Historia de Usuario.  
  (Ejemplo: `HU-1`, `HU-5`, etc.)
- ✅ La descripción debe ser breve, clara y en tiempo presente.
- ✅ No usar descripciones genéricas como `update code` o `misc changes`.

---
