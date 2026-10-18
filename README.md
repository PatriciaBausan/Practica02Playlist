# ZOUND - Reproductor Musical 🎵

## 📌 Descripción
ZOUND es una aplicación web interactiva que funciona como un reproductor de música completo, desarrollada como proyecto de Desarrollo Web en Entorno Cliente. 

La aplicación permite al usuario cargar una lista de reproducción predefinida, escuchar canciones, visualizar información detallada de la pista actual y modificar el audio en tiempo real mediante un ecualizador visual dinámico.

## 🎯 Funcionalidad Principal

El reproductor cumple con las siguientes características:

### 1. Reproducción de Audio 🎧
- Permite interactuar con los controles principales: **Play/Pause, Anterior (Back) y Siguiente (Forward)**.
- Integración de modos adicionales: **Reproducción Aleatoria** y **Repetir**.
- Muestra los datos actualizados de la canción que está sonando (título, artista y portada/imagen).
- Control de **volumen** ajustable en todo momento.
- Barra de **progreso interactiva** que permite adelantar o retroceder la canción arrastrando el control.

### 2. Lista de Reproducción 📋
- La lista de canciones se genera de forma dinámica al iniciar la web mediante JavaScript.
- Al hacer clic en cualquier canción de la lista, se detiene la pista actual y comienza a reproducirse la seleccionada en el reproductor principal.
- Diseño responsivo con un contenedor de lista adaptable que incluye un **scroll interno** para navegar cómodamente cuando hay muchas canciones, manteniendo el diseño limpio sin que las canciones se aplasten.

### 3. Modificación del Audio y Ecualizador 🎛️
- Dispone de un **Ecualizador en vivo** (Visualizador animado) que reacciona a las frecuencias de la música que se está reproduciendo.
- Permite modificar los ajustes del sonido en tiempo real controlando los **Graves, Medios y Agudos** (en decibelios).
- Incluye un botón para **Restablecer** los valores del ecualizador a su estado original (0 dB).

## 📁 Estructura del proyecto

```text
Practica 2
│
├── index.html          # Estructura principal de la aplicación web
│
├── css/                # Carpeta de estilos
│   └── style.css       # Diseño visual, animaciones y layout dinámico
│
├── js/                 # Lógica de la aplicación 
│   └── app.js          # Control del reproductor, ecualizador web audio y playlist
│
├── audio/              # Archivos de sonido
│   ├── Prefekt.mp3     
│   ├── ...             
│   └── Adeus.mp3       
│
└── imagenes/           # Portada de las imágenes de las canciones
    ├── prefekt.png     
    ├── ...             
    └── Adeus.png       
```

---
## 💻 Tecnologías utilizadas
- **HTML5** — Estructura semántica del reproductor.
- **CSS3** — Diseño responsivo, variables CSS, Flexbox/Grid y animaciones avanzadas.
- **JavaScript** — Lógica del reproductor, manipulación del DOM y control de audio.
- **Howler.js** — Librería externa utilizada para el manejo avanzado y simplificado del audio web y los nodos del ecualizador.
- **Web Audio API** — Uso nativo para la creación de los filtros Biquad (Graves, Medios, Agudos) y el AnalyserNode para el visualizador.
- **Git & GitHub** — Control de versiones y alojamiento del código.

## 👩‍💻 Autora
**Patricia Bausan Gómez**  
Proyecto realizado para el ciclo de Desarrollo de Aplicaciones Web (DAW).

## 📚 Proyecto académico
Este proyecto ha sido desarrollado como práctica modular de Desarrollo Web en Entorno Cliente, enfocándose en la manipulación del DOM, el uso de librerías externas de audio y el diseño de interfaces de usuario interactivas.
