# 🐧 Linux For Noobs

Landing page informativa y educativa pensada para desmitificar Linux: presentarlo como una alternativa real, moderna y accesible para cualquier persona, no solo para "expertos" o programadores.

🔗 **Sitio publicado:** https://linuxfornoobs.netlify.app/
🎨 **Diseño en Figma:** https://www.figma.com/design/uxqW0Gxd5WBv88C6FgvI9E/Linux-For-Noobs

---

## 🧭 Proceso de trabajo

Este proyecto se desarrolló como ejercicio obligatorio de **Mujeres Programando Futuro** (Fundación Mediapila). No partió de una plantilla ni de una idea genérica: siguió un proceso real de desarrollo con un cliente ficticio (una persona real, tomada como cliente para el ejercicio).

1. **Relevamiento** — conversación con la persona "cliente" para entender qué necesitaba comunicar, a quién iba dirigida la web y qué problema buscaba resolver. Esa conversación quedó documentada (preguntas, respuestas y síntesis) antes de tocar el diseño.
2. **Diseño en Figma** — el diseño respondió directamente a lo relevado: estructura, contenido y jerarquía pensados para el público real (principiantes curiosos por Linux), no genéricos.
3. **Desarrollo** — el código respeta el diseño aprobado, priorizando coherencia entre lo diseñado y lo construido por sobre la perfección técnica.
4. **Publicación** — el sitio se subió a Netlify de forma autónoma, investigando el proceso de deploy sin guía paso a paso.

## 🎯 Propósito

El sitio está dirigido a usuarios principiantes y a personas que vienen de Windows/macOS con curiosidad por el software libre, pero que sienten que Linux "es solo para expertos". La idea es que quien la visite entienda qué es Linux, vea sus ventajas y se anime a explorar por su cuenta qué distribución instalar.

Es una guía de referencia estática (una sola página), sin formularios ni backend.

## 📐 Secciones

* **Inicio (Hero)** — presentación principal
* **Definición** — qué es Linux, el kernel y GNU/Linux
* **¿Por qué Linux?** — ventajas frente a otros sistemas operativos
* **Distribuciones** — Ubuntu, Fedora, Linux Mint, Zorin, entre otras
* **Entornos de Escritorio (D.E)** — GNOME, XFCE, KDE
* **Aprender Más** — video y recursos para seguir investigando

## 🛠️ Tecnologías

* HTML5 y CSS3
* Bootstrap 5 y Bootstrap Icons
* Tipografías [JetBrains Mono](https://www.jetbrains.com/lp/mono/) (títulos, look técnico) e [Inter](https://fonts.google.com/specimen/Inter) (texto de lectura larga)
* Sin JavaScript ni backend — sitio 100% estático

## 🎨 Diseño

Estética moderna y técnico-minimalista, inspirada en sitios de documentación como Tailwind CSS o las landing pages de Vercel: tipografía técnica y colores vibrantes sobre fondos limpios.

* **Colores:** Naranja `#F09400`, Negro y Blanco
* **Estilo:** limpio, ordenado, con guiños a la estética del software (código, tipografía monoespaciada)

## 📁 Estructura del proyecto

```text
Linux-For-Noobs/
├── index.html          # Estructura de la página (todas las secciones)
├── styles.css          # Estilos personalizados
├── icons/               # Logos oficiales (Tux, Ubuntu, Fedora, Mint, Zorin, GNOME, XFCE, KDE)
└── imagenes/            # Imágenes propias del sitio (Tux, Linus Torvalds)
```

## ⚡ Cómo verlo localmente

No requiere instalación ni dependencias — es HTML y CSS puro.

1. Cloná o descargá el repositorio
2. Abrí `index.html` directamente en el navegador

o, si preferís evitar restricciones de CORS al cargar los estilos, usá una extensión como **Live Server** en VS Code.
