# ⚽ Marcador de Fútbol - App Prueba

Este es un proyecto interactivo desarrollado con **React** y empaquetado utilizando **Vite**. Su objetivo principal es funcionar como un marcador de fútbol dinámico para gestionar partidos, resultados y reinicio de estadísticas. 

---

### 🛠️ Lo que ya está subido:
* **Configuración del Entorno:** Configuración completa de Vite (`vite.config.js`), dependencias del proyecto (`package.json`), y reglas de linter (`eslint.config.js`).
* **Estilos Estructurados:** Archivos CSS globales (`App.css` e `index.css`) listos para personalizar la interfaz.
* **Componentes Base (Estructura):** Se crearon los archivos `.jsx` en la carpeta `src/componentes/` que dividirán la aplicación:
  * `Partido.jsx`: Diseñado para controlar el marcador individual y los goles.
  * `Match.jsx`: Añadido componente base para evitar errores de compilación (estructura de soporte para jornadas).
  * `Restart.jsx`: Destinado al botón de reinicio de tiempos y puntajes.
  * `ResultText.jsx`: Diseñado para mostrar mensajes de estado (ganador, empate, etc.).

---

## 🚀 Cómo Ejecutar el Proyecto Localmente

Para levantar este proyecto en tu entorno local por primera vez, sigue estos pasos desde tu terminal en la raíz de la carpeta:

1. **Instalar dependencias:**
   ```bash
   npm install