# 🎯 Adivina el Número con Contador de Intentos

Juego clásico de adivinar un número aleatorio entre 1 y 100, con retroalimentación de "más alto"/"más bajo", contador de intentos en vivo e interfaz de tema oscuro. Construido con **HTML, CSS y JavaScript puro**.

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

## 🔗 Proyecto en vivo

👉 [Ver proyecto en vivo](https://number-riddle.netlify.app/)

## ✨ Características

- Número aleatorio generado entre **1 y 100** al cargar la página.
- Retroalimentación en cada intento: "más alto" o "más bajo" según la comparación con el número ingresado.
- **Contador de intentos** actualizado en tiempo real, destacado con color de acento.
- **Validación de entrada**: rechaza valores fuera del rango 1-100 o no numéricos, mostrando un mensaje claro.
- El input se **deshabilita correctamente** (`disabled = true`) al acertar, bloqueando intentos adicionales.
- Diseño con **tema oscuro** y acentos violeta, tarjeta centrada con sombra y flechas nativas del input numérico ocultas para un look más limpio.

## 🛠️ Tecnologías utilizadas

- **HTML5** — estructura simple con input numérico, botón y áreas de mensaje/estadísticas.
- **CSS3** — tema oscuro con variables de color consistentes, estados de foco y deshabilitado (`:disabled`), y ocultado de spin buttons nativos (`::-webkit-inner-spin-button`).
- **JavaScript (Vanilla)** — generación de número aleatorio con `Math.random()`, comparación con `parseInt()` y validación con `isNaN()`.

## 📂 Estructura del proyecto

```
├── index.html
├── style.css
├── script.js
└── README.md
```

## 🚀 Cómo usarlo localmente

1. Clona el repositorio:
   ```bash
   git clone https://github.com/carlos-daniel07/guess-the-number-game.git
   ```
2. Entra a la carpeta del proyecto:
   ```bash
   cd guess-the-number-game
   ```
3. Abre `index.html` en tu navegador (o usa la extensión Live Server en VS Code).

## 🎮 Cómo jugar

- Escribe un número entre 1 y 100.
- Presiona "Comprobar".
- Sigue las pistas de "más alto"/"más bajo" hasta acertar. Al ganar, el campo se bloquea automáticamente.

## 🧠 Qué aprendí / practiqué

- Generar un número aleatorio acotado a un rango con `Math.floor(Math.random() * 100)`.
- Validar entradas numéricas combinando rango (`< 1`, `> 100`) y verificación de `NaN` en un mismo condicional.
- Dar feedback progresivo al usuario (mayor/menor) en vez de solo indicar acierto o error.
- Deshabilitar correctamente un input tras completar una acción (`element.disabled = true`) para evitar interacciones no deseadas después del estado final.

## 📸 Vista previa

<img width="1920" height="1536" alt="image" src="https://github.com/user-attachments/assets/277d96aa-b071-4cbd-885e-510f5d167412" />

## 📄 Licencia

Este proyecto es de uso libre con fines educativos y de portfolio.

---

Hecho con 💻 por [Carlos Daniel](https://github.com/carlos-daniel07)
