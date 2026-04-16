# Proyecto Final - Taller HTML/CSS + Git

Proyecto web académico desarrollado colaborativamente utilizando HTML, CSS y control de versiones con Git/GitHub.

---

## 📁 Árbol de archivos

```
TallerFinal/
├── index.html       # Estructura principal de la página
├── style.css        # Estilos externos (paleta, tabla, formulario, galería)
└── README.md        # Documentación del proyecto
```

---

## 🚀 Instrucciones de uso

### 1. Clonar el repositorio
```bash
git clone https://github.com/Jairo-LP/TallerFinal
cd TallerFinal
```

### 2. Abrir el proyecto
Abre el archivo `index.html` directamente en tu navegador, o usa la extensión **Live Server** de VS Code para verlo en `127.0.0.1:3000`.

### 3. Realizar cambios
Crea siempre una rama nueva antes de editar:
```bash
git checkout -b feature/nombre-de-tu-cambio
git add .
git commit -m "descripción del cambio"
git push origin feature/nombre-de-tu-cambio
```

---

## 📖 Guía de usuario

La página está compuesta por las siguientes secciones:

- **Encabezado y navegación** — acceso rápido a las secciones principales.
- **Lista de Estudiantes** — tabla con datos de ID, nombre, carrera, semestre y promedio.
- **Registro** — formulario con campos de nombre, correo y mensaje.
- **Acerca de** — descripción del proyecto con tarjetas de objetivo, tecnologías y diseño.
- **Galería** — cuadrícula 2×2 con imágenes de muestra usando CSS Grid.

La página es **responsiva**: en pantallas menores a 600px la tabla se convierte en bloques apilados y la navegación se muestra en columna.

---

## 🤝 Reflexión colaborativa

Este proyecto fue desarrollado en pareja como práctica de trabajo colaborativo con Git. Cada integrante trabajó en su propia rama:

- **Estudiante A** añadió la sección Galería/Grid con CSS Grid y 4 imágenes.
- **Estudiante B** añadió la sección Acerca de y mejoró la responsividad del formulario y la tabla con media queries.

Durante el proceso, ambos editaron intencionalmente la misma línea del archivo `style.css` (el color de fondo del encabezado de tabla `table th`), lo que generó un **conflicto de fusión** al hacer merge. Este conflicto fue resuelto manualmente en el editor de VS Code, eligiendo el valor final de color y confirmando la resolución

```bash
git add .
git commit -m "fix: resolver conflicto en estilos de tabla"
```

Esta experiencia permitió comprender de forma práctica cómo Git detecta conflictos, cómo leerlos dentro del archivo y cómo resolverlos sin perder el trabajo de ninguno de los dos colaboradores.

---

*Proyecto Final — Git + HTML/CSS © 2025*