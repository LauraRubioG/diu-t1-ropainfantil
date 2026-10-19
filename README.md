# 🦆 PicoPato — Moda infantil a un toque

![Pantalla destacada de PicoPato](<capturas/prototipo/0 - Inicio sesión.png>)

> **Tarea 1: Documentación y prototipo Material Design 3 en Figma**
> *Aplicación de tienda de ropa y calzado infantil (0 a 14 años)*

---

## 📑 Índice
1. Sobre el proyecto
2. Enlaces de Figma (Entregables)
3. El enfoque UX: Diseño para el mundo real
4. Estructura del repositorio
5. Notas para la evaluación

---

## 1. Sobre el proyecto
¡Bienvenidos a **PicoPato**! 👕👟 

Esta aplicación nace con un objetivo muy claro: **hacerle la vida más fácil a las familias**. Comprar ropa para los peques no debería ser un dolor de cabeza. Sabemos que nuestro público principal (madres, padres, abuelos y gente que busca el regalo perfecto) vive a mil por hora. Muchas veces tienen que comprar desde el móvil mientras sostienen a un niño con el otro brazo, dudan con los tallajes o tienen miedo a equivocarse al pagar.

Por eso, PicoPato no es solo una tienda bonita, es una herramienta diseñada desde la empatía y la usabilidad, aplicando las directrices de **Material Design 3 (M3)** para ofrecer una experiencia de compra limpia, rápida y sin frustraciones.

---

## 2. Enlaces de Figma (Entregables)

A continuación se encuentran los enlaces directos al espacio de trabajo. El archivo principal está configurado con permisos de edición para la docente.

*   🎨 **[Archivo de diseño en Figma (Editable)]** -> [ARCHIVO_DE_FIGMA](https://www.figma.com/design/Z7zB8doIT20S0F7ZJQeOlc/T1-%C2%B7-PicoPato-%C2%B7-Laura-Rubio?node-id=33-62&t=iR2TMuebXli6hejj-1)
*   📱 **[Prototipo Interactivo de Alta Fidelidad]** -> [PROTOTIPO_PLAY](https://www.figma.com/proto/Z7zB8doIT20S0F7ZJQeOlc/T1-%C2%B7-PicoPato-%C2%B7-Laura-Rubio?node-id=55-1337&p=f&viewport=121%2C-40%2C0.54&t=kAv8HwdBjPDAOXoE-1&scaling=min-zoom&content-scaling=fixed&starting-point-node-id=55%3A1337&page-id=33%3A62)

---

## 3. El enfoque UX: Diseño para el mundo real
Para construir la interfaz de PicoPato, no nos hemos quedado en la capa estética. Hemos bajado al barro para entender cómo usa el móvil nuestro usuario real. La aplicación destaca por:

*   **Navegación a una mano (Thumb Zone):** Todos los botones clave, como el *Call to Action* principal ("Añadir al carrito"), el selector de tallas y la barra de navegación, están anclados en la zona inferior de la pantalla. Todo está a un golpe de pulgar.
*   **Adiós a las dudas con las tallas:** Hemos implementado un *Bottom sheet* interactivo para la guía de tallas. Los abuelos o padres pueden consultar los centímetros y equivalencias sin tener que salir de la pantalla de producto, evitando que pierdan el hilo de la compra.
*   **Prevención y recuperación de errores:** Si un usuario elimina por accidente un producto del carrito, aparece inmediatamente un *Snackbar* con la opción "Deshacer". En el *Checkout*, los *Text Fields* advierten de los errores en tiempo real usando el color rojo semántico de M3 (`#BA1A1A`) y mensajes de ayuda claros.
*   **Identidad limpia y accesible:** Utilizando *Material Theme Builder*, hemos generado un esquema de colores basado en un tono azul sereno (`#61859A`). Esto transmite calma, asegura un contraste matemático (WCAG AA) perfecto y permite que la ropa sea la verdadera protagonista visual, tanto en el Modo Claro como en el Modo Oscuro.

---

## 4. Estructura del repositorio

El repositorio está organizado exactamente como exige la rúbrica del proyecto, centralizando toda la información, estilos y capturas en sus respectivas carpetas:

```text
diu-t1-ropainfantil/
├── README.md              ← (Estás aquí) Portada, índice y enlaces a Figma.
├── DOCUMENTACION.md       ← Documento principal con la investigación, wireframes, validación e iteración (Secciones 1 a 6).
├── diseno/
│   └── estilos.json       ← Tokens de la guía de estilo Material Design 3 (esquemas y tipografía).
└── capturas/
    ├── wireframes/        ← Pantallas de baja fidelidad.
    ├── prototipo/         ← Pantallas de alta fidelidad (modo claro y oscuro).
    └── iteracion/         ← Capturas del antes y el después de las pruebas de usabilidad.