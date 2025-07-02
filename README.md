# 💡 Mentes Fuertes, Redes Conscientes

**Mentes Fuertes, Redes Conscientes** es una aplicación web educativa y motivacional enfocada en brindar apoyo emocional a jóvenes mediante contenido inspirador, recursos descargables y un chat interactivo de acompañamiento. El sitio está diseñado para ser seguro, accesible, ligero y adaptable a cualquier dispositivo.

---

## 📌 Características Principales

- 🧠 **Chat de Apoyo Emocional** con respuestas automatizadas y advertencias de seguridad.
- 📰 **Publicaciones Motivacionales** dinámicas administrables (CRUD en el frontend).
- 📥 **Recursos descargables** (guías, ejercicios, videos).
- 🔎 **Buscador y Filtro Dinámico** por categoría.
- 🔐 **Panel de Administración Protegido** por contraseña.
- 🛡️ **Validaciones de seguridad**: XSS, control de roles, entradas vacías.
- 📱 **Diseño responsivo y optimizado** para móviles, tablets y escritorio.
- 🌐 **Integración con redes sociales**, Google Fonts y FontAwesome.

---

## 🛠 Tecnologías Utilizadas

### Frontend
- HTML5 + CSS3
- JavaScript (Vanilla)
- FontAwesome
- Google Fonts (Montserrat)

### Herramientas y Plataformas
- Git + GitHub (control de versiones)
- Netlify (despliegue continuo)
- VS Code (editor)
- Trello / Notion (gestión ágil)

---

## 🏗 Arquitectura

- Arquitectura modular basada en el patrón **MVC del lado cliente**.
- Separación entre lógica (controlador), datos (`localStorage` como modelo), y visualización (HTML/CSS).
- Patrones aplicados: **Modular JS**, **Singleton**, **Observer**, **Factory**.

---

## 🔒 Seguridad

- Validación de entradas en todos los formularios.
- Prevención de XSS en el chat.
- Autenticación con contraseña para el modo admin.
- Advertencias visuales para prácticas seguras.
