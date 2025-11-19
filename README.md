# LIBRO-DE-TEMAS
# 📚 LIBRO DE TEMAS: Propuesta de Digitalización del Libro de Temas

## Resumen del Proyecto y Propuesta de Valor

LIBRO DE TEMAS es el proyecto final de carrera que presenta la propuesta conceptual y de diseño para digitalizar los libros de temas en las instituciones educativas.

Este sistema está diseñado para:
1.  **Optimizar el tiempo** del personal docente y directivo.
2.  **Centralizar y asegurar** el registro de temas y la validación de clases.
3.  **Eliminar el uso de papel** y los errores asociados al manejo manual de los libros.

El proyecto incluye el diseño completo de una aplicación móvil y una plataforma web, modeladas para una interacción intuitiva y eficiente.

---

## 🎨 Fase de Diseño Conceptual y Funcional

El diseño y la simulación funcional del sistema fueron desarrollados íntegramente utilizando la siguiente herramienta:

* **Herramienta de Diseño:** **Figma**
    * Se utilizó Figma para crear los **wireframes** (esquemas) y los **prototipos de alta fidelidad** de la aplicación móvil y la plataforma web.
    * Se implementó una **simulación funcional** dentro de Figma para demostrar el flujo de trabajo completo (inicio de sesión, registro de temas, validación por el directivo).

> **Enfoque del Diseño:** El diseño se centró en la usabilidad (**UX/UI**) para asegurar que la transición del libro de papel al digital sea lo más fluida y natural posible para todos los usuarios (preceptores, profesores y directivos).

---

## 🚀 Propuesta de Pila Tecnológica (Tech Stack)

A continuación, se presenta la **pila tecnológica recomendada** para la futura implementación del programa. Esta selección se basa en la **escalabilidad, el rendimiento y la eficiencia** del desarrollo multiplataforma.

### 🌐 Frontend (Interfaces de Usuario)
| Componente | Tecnología Propuesta | Razón Clave para la Decisión |
| :--- | :--- | :--- |
| **Aplicación Móvil** | **React Native** (con TypeScript) | Permite construir una **aplicación nativa** de alta calidad (iOS/Android) desde una **única base de código**, optimizando el mantenimiento futuro. |
| **Aplicación Web** | **React** (con TypeScript) | Framework líder para interfaces de usuario complejas (paneles de reportes y administración), manteniendo la **consistencia** con React Native. |

### ⚙️ Backend (Servidor y Lógica de Negocio)
| Componente | Tecnología Propuesta | Razón Clave para la Decisión |
| :--- | :--- | :--- |
| **API** | **Node.js con Express / NestJS** | Entorno de ejecución rápido y escalable. Mantiene el desarrollo en un único ecosistema de lenguaje (**JavaScript/TypeScript**), facilitando la gestión del equipo. |

### 🗄️ Base de Datos
| Componente | Tecnología Propuesta | Razón Clave para la Decisión |
| :--- | :--- | :--- |
| **Base de Datos** | **PostgreSQL** | Base de datos relacional robusta. Es esencial para garantizar la **integridad transaccional** y la estricta relación de los datos críticos (firmas, roles, clases), vital para un registro institucional. |

---

## 📐 Estructura de Usuarios y Roles

La funcionalidad del diseño se basa en una estricta gestión de roles, con diferentes permisos para cada tipo de usuario:

| Rol | Plataforma de Uso Primario | Acciones Clave |
| :--- | :--- | :--- |
| **Profesor** | Móvil | Iniciar sesión, **registrar el tema** de la clase, ver su horario. |
| **Preceptor** | Móvil / Web | Controlar la asistencia, asignar reemplazos, generar el registro de clase para el profesor. |
| **Directivo** | Web | **Validar y Firmar** digitalmente las clases registradas, acceder a reportes y auditoría histórica. |

---

## 👨‍💻 Autores del Diseño y Documentación

Este proyecto fue desarrollado por los estudiantes de 3er año de Desarrollo de Software:

---

## 🔗 Enlaces Importantes

* **Prototipo Interactivo en Figma:** [Insertar el link de 'Share' o 'Prototype' de Figma aquí]
* **Documentación de Requisitos Funcionales:** [Link al documento de requisitos (opcional)]
