# 🎸 Bajo Eléctrico para Eloisa 🎸

Una aplicación web progresiva (PWA) de un bajo eléctrico, optimizada para dispositivos móviles y diseñada para que Eloisa pueda practicar y divertirse.

## ✨ Características Principales

### 📱 Optimizaciones para Móviles
*   **Progressive Web App (PWA):**
    *   Instalable en el celular como una aplicación nativa.
    *   Funciona sin conexión después de la primera carga.
    *   Meta tags específicos para una experiencia nativa en iOS y Android.
*   **Interacciones Táctiles:**
    *   Vibración al tocar las cuerdas para una respuesta háptica (`vibrate([30])`).
    *   Botones grandes (mínimo `44px`) para facilitar el uso con los dedos.
    *   Feedback visual inmediato al tocar (`scale(0.95)`).
    *   Eventos `onTouchEnd` para una respuesta más rápida.
*   **Detección Automática de Dispositivo:**
    *   La interfaz se adapta automáticamente a pantallas de móvil.
    *   Textos más pequeños y un diseño de bajo más compacto en móviles.
    *   Menos animaciones para un mejor rendimiento.
*   **Rendimiento Optimizado:**
    *   Análisis de audio de menor complejidad (`fftSize: 1024`).
    *   Animaciones fluidas y rápidas.
    *   DOM más ligero en la versión móvil.

### 💖 Funcionalidades Adicionales
*   **Efectos Divertidos:**
    *   Corazones animados que vuelan por la pantalla.
    *   Vibración especial al recibir premios.
    *   Emojis en cada cuerda.
    *   Animaciones llamativas para los premios.
*   **🎤 Detección de Audio:**
    *   Micrófono optimizado para móviles.
    *   Detecta las notas tocadas en un bajo real.
    *   Feedback visual al tocar la nota correcta.
*   **🏆 Gamificación:**
    *   Sistema de puntos y rachas para mantener la motivación.
    *   Logros acumulables.
    *   Lecciones progresivas con guía paso a paso.

## 🚀 Despliegue en GitHub Pages (¡Gratis!)

Sigue estos sencillos pasos para publicar la aplicación online:

1.  **Guardar el Archivo:**
    *   Copia el código del artifact y guárdalo en un archivo llamado `index.html`.
2.  **Crear Repositorio y Subir Archivo:**
    *   En GitHub, ve a **New repository**.
    *   Nombra el repositorio (ej. `bajo-electrico-eloisa`).
    *   Selecciona **Upload files**, arrastra tu archivo `index.html` y haz clic en **Commit changes**.
3.  **Activar GitHub Pages:**
    *   En tu repositorio, ve a **Settings** > **Pages**.
    *   En **Deploy from a branch**, selecciona la rama `main` y haz clic en **Save**.

**¡Listo!** En unos minutos tendrás una URL pública para que Eloisa pueda usar la aplicación desde cualquier dispositivo.

## ✅ Resumen de Ventajas

*   **PWA instalable** en el celular.
*   **Vibración táctil** para una mejor experiencia.
*   **Detección de micrófono** funcional.
*   **Diseño responsive** para móvil y escritorio.
*   **Totalmente gratis** y sin necesidad de servidores.

¡Eloisa va a estar súper emocionada! Esta versión es la más completa y optimizada posible 🎸💕
