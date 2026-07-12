<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/🇪🇸-ES-ff4b4b?style=for-the-badge&labelColor=1a1a2e" alt="Español"></a>
  <a href="README.EN.md"><img src="https://img.shields.io/badge/🇬🇧-EN-4b8bff?style=for-the-badge&labelColor=1a1a2e" alt="English"></a>
  <a href="README.IT.md"><img src="https://img.shields.io/badge/🇮🇹-IT-2ecc71?style=for-the-badge&labelColor=1a1a2e" alt="Italiano"></a>
</p>

# 📄 Personal Resume — Demo

Currículum web estático multiidioma generado como **página demo** del proyecto principal [CV para Todos](https://github.com/RaulMartinGuerrero/CV-para-todos).

Este repositorio contiene la versión exportada y estática de un CV construido con la plantilla **techy** del generador. Está diseñado para mostrarse como ejemplo vivo de lo que cualquier usuario puede crear con el proyecto principal.

---

🌐 **[Ver Demo en Vivo](https://rmartinguerrero.github.io/personal-resume/)**

---

## ✨ Características

* 🌍 **Multiidioma Nativo:** Soporta Español, Inglés e Italiano con detección automática del idioma del navegador.
* 🎨 **Plantilla Techy:** Diseño técnico y oscuro con tipografía JetBrains Mono e Inter.
* ⚡ **Rendimiento Óptimo:** Página estática HTML/CSS/JS sin dependencias de backend ni frameworks pesados.
* 📱 **Totalmente Responsivo:** Se adapta a cualquier tamaño de pantalla.
* 🔒 **Privacidad:** Sin cookies, sin rastreadores, sin telemetría.

---

## 📁 Estructura del Proyecto

```
├── index.html            # Página de entrada (redirección automática al idioma)
├── style.css             # Estilos unificados con 3 temas (minimalist, techy, artistic)
├── profile.webp          # Foto de perfil
├── resume.es.json        # Datos del CV en español (estándar JSON Resume)
├── resume.en.json        # Datos del CV en inglés
├── resume.it.json        # Datos del CV en italiano
├── es/index.html         # CV renderizado en español
├── en/index.html         # CV renderizado en inglés
├── it/index.html         # CV renderizado en italiano
└── .nojekyll             # Evita el procesamiento de Jekyll en GitHub Pages
```

---

## 🚀 Despliegue

El sitio está desplegado en **GitHub Pages** y se actualiza automáticamente al hacer push al repositorio.

### Desarrollo Local

Para previsualizar la demo localmente, basta con abrir `index.html` en un navegador o usar un servidor local:

```bash
# Con Python
python -m http.server 8000

# Con Node.js
npx serve .
```

---

## 🔗 Proyecto Principal

Este repositorio es una demo estática del proyecto completo:

> 👉 **[CV para Todos](https://github.com/RaulMartinGuerrero/CV-para-todos)** — Currículum web multiidioma, open-source, con editor visual No-Code y despliegue automático.

---

## 🤖 Desarrollo Asistido por IA

Este proyecto ha sido desarrollado con la ayuda de herramientas de Inteligencia Artificial como apoyo durante el diseño, la programación y la documentación.

Todas las decisiones finales corresponden a **Raúl Martín Guerrero**.

---

## 📜 Licencia

Este proyecto está distribuido bajo la **GNU General Public License v3.0 (GPL-3.0)**.

Copyright © 2026 Raúl Martín Guerrero

## 🧠 Autor

Proyecto desarrollado por **Raúl Martín Guerrero**.
