## 📌 Nomenclatura de Ramas

Para mantener el repositorio organizado y facilitar el trabajo en equipo, se establece la siguiente convención para nombrar las ramas:

### Formato general:

---

### Tipos de ramas permitidos:

| Tipo         | Prefijo        | Uso                                      |
|--------------|----------------|-----------------------------------------|
| **Feature**  | `feature/`     | Desarrollo de nuevas funcionalidades. |
| **Fix**      | `fix/`         | Corrección de errores o bugs. |
| **Refactor** | `refactor/`    | Mejoras internas del código, sin añadir nueva funcionalidad. |
| **Hotfix**   | `hotfix/`      | Correcciones urgentes en producción. |
| **Release**  | `release/`     | Preparación de una nueva versión para despliegue. |

---

### Ejemplos de nombres de ramas:

- `feature/HU-1-registro-de-usuario`
- `feature/HU-3-inicio-de-sesion`
- `fix/HU-5-error-en-creacion-de-tareas`
- `refactor/limpieza-de-servicios`
- `hotfix/error-en-produccion-login`
- `release/v1.0.0`

---

### Reglas básicas:

- ✅ Usa solo **minúsculas**.
- ✅ Separa las palabras con **guiones medios** (`-`).
- ✅ Incluye el ID de la Historia de Usuario cuando corresponda.
- ✅ Sé claro y descriptivo pero breve.
- 🚫 Evita nombres genéricos como `new-branch` o `update`.