# Crash Team Racing Nitro-Fueled: PC-Port Experience Pack (v1.0.15)

¡Bienvenido! Este repositorio contiene una suite modular de mods diseñada para transformar la versión de Nintendo Switch de **Crash Team Racing Nitro-Fueled** en la experiencia definitiva de un Port para PC, logrando **60 FPS rocosos a altas resoluciones (hasta 1620p/x1.5)** incluso en tarjetas gráficas modestas como una GTX 1650.

## 🚀 Características del Pack
- **Rendimiento Liberado:** Al eliminar sombreadores pesados y optimizar partículas, se libera suficiente potencia para aumentar la resolución interna del emulador sin perder frames.
- **Modularidad Completa:** Todos los parches están separados en formato `.pchtxt`. Puedes elegir exactamente qué efectos visuales mantener y cuáles quitar según la potencia de tu PC.
- **Listo para el Competitivo:** Diseñado para mantener la fluidez milimétrica necesaria para encadenar *Perfect Drifts* y mantener el *Sacred Fire* sin micro-stutters.

## 🛠️ Módulos Disponibles (.pchtxt)
Puedes activar los siguientes mods de manera independiente en tu emulador:
- `30 FPS Stable & Disable Dynamic Res`: Fija los FPS nativos y desactiva el borroso escalado dinámico.
- `Disable Motion Blur & FXAA`: Quita el emborronamiento al derrapar y el filtro analógico.
- `Disable Fog & Depth of Field (DoF)`: Elimina la niebla pesada de fondo y el desenfoque de distancia.
- `No Floor Marks & Low Quality Shadows`: Desactiva las marcas de neumáticos en el suelo y simplifica las sombras.
- `Simplify Heavy Effects & Smoke`: Reduce partículas de explosiones y el humo de los tubos de escape.
- `Simplify Animals Fur`: Reemplaza el pesado pelaje dinámico de los personajes por texturas estáticas (ahorra toneladas de VRAM).
- `Single Channel Audio`: Mezcla el audio en un canal monoaural para reducir el estrés en la CPU.

---

## ⚙️ Configuraciones del Emulador (Eden, Yuzu, Ryujinx, etc.)

Aplica estos ajustes para replicar mi configuración exacta o adaptar el juego a tu hardware:

*   **💻 Sistema:** 
    *   Si tienes una **PC Patata (Gama Baja)** dejalo en *Handheld (Portátil)*: reduce la resolución y detalles pero ganas muchos FPS.
    *   Para **PCs más potentes**, déjalo en *Docked (Sobremesa)*: tiene mayor detalle y resolución, aunque consume más.
    *   Activa siempre la opción **"Synchronize Core Speed"**.
    *   *Tip de audio:* Si notas chasquidos en el sonido al jugar a 60 FPS con el parche, sube el búfer de audio a **100 ms** en la sección de audio para corregir la sincronización del motor.

*   **🧠 CPU:**
    *   Déjalo en **Unsafe** si quieres máximos FPS (aunque puede dar más bugs visuales).
    *   Déjalo en **Accurate** si quieres la menor cantidad de errores (pero consume más).
    *   Déjalo en **Auto** si no sabes qué hacer.

*   **🎨 Gráficos:**
    *   **API:** Déjala en **Vulkan** sí o sí. Si no te inicia el juego o se te queda en negro, prueba en *OpenGL* (pero de manera normal, usa Vulkan).
    *   **Resolución:** Es recomendable dejarlo en **1x hacia abajo** (1x equivale a 720p en portátil y 1080p en sobremesa). Súbela si tienes una PC más potente (Recomendado **1.25x** o **1.5x** para lograr 1620p).
    *   **VSync:** Déjalo en **FIFO (Activado)**.
    *   **Window Adapting Filter:** Déjalo en **Bilinear** para las PC Patata (Gama Baja) y en **AMD Super Resolution** para PCs un poco más potentes.

*   **🚀 Gráficos Avanzados:**
    *   **GPU Mode:** Déjalo en **Fast** si quieres máximos FPS, y en **Accurate** para la menor cantidad de errores visuales. *(Si quieres mi configuración exacta, déjalo en Accurate, aunque si te faltan FPS pásalo a Fast)*.
    *   **Anisotropic Filter:** Recomiendo dejarlo en **2x, 4x o Predeterminado** (si lo subes más se verá mejor, pero consumirá más).
    *   **ASTC Recompression Method:** Recomiendo dejarlo en **BC3 y BC1**. No cambiará nada visualmente y suma muchísimos FPS.
    *   Activa las casillas **"Force Maximum Clocks"** (Solo funciona en Vulkan) y **"Sync to Framerate of Video Playback"**.

*   **🔌 Extensiones Gráficas:**
    *   Activa **"Fix Bloom Effects"** y **"Enable Asynchronous Shader Compilation"**.

---

## ⚠️ Nota del Autor
Debido a que las Boxes (*Pit Stop*) requieren conexión a servidores oficiales de Activision, se recomienda encarecidamente instalar un **Save Game al 100%** en la carpeta de usuario de tu emulador para tener desbloqueados todos los personajes (como Spyro o Nina Cortex) y todas las skins desde el primer segundo.

*Disfruta de este juegazo a maximos FPS!*
