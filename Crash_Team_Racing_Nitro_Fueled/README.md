# Crash Team Racing Nitro-Fueled: PC-Port Experience Pack (v1.0.15)

¡Bienvenido! Este repositorio contiene una suite modular de mods diseñada para transformar la versión de Nintendo Switch de **Crash Team Racing Nitro-Fueled** en la experiencia definitiva de un Port para PC, logrando **60 FPS rocosos a altas resoluciones (hasta 1620p/x1.5)** incluso en tarjetas gráficas modestas como una GTX 1650.

## 🚀 Características del Pack
- **Rendimiento Liberado:** Al eliminar sombreadores pesados y optimizar partículas, se libera suficiente potencia para aumentar la resolución interna del emulador sin perder frames.
- **Modularidad Completa:** Todos los parches están separados en formato `.pchtxt`. Puedes elegir exactamente qué efectos visuales mantener y cuáles quitar según la potencia de tu PC.
- **Listo para el Competitivo:** Diseñado para mantener la fluidez milimétrica necesaria para encadenar *Perfect Drifts* y mantener el *Sacred Fire* sin micro-stutters.

## 🛠️ Módulos Disponibles (.pchtxt)
Puedes activar los siguientes mods de manera independiente en tu emulador (Eden):
- `30 FPS Stable & Disable Dynamic Res`: Fija los FPS nativos y desactiva el borroso escalado dinámico para una imagen nítida constante.
- `Disable Motion Blur & FXAA`: Quita el emborronamiento al derrapar y el filtro analógico para ganar claridad visual.
- `Disable Fog & Depth of Field (DoF)`: Elimina la niebla pesada de fondo y el desenfoque de distancia (ideal para pistas como *Cortex Castle*).
- `No Floor Marks & Low Quality Shadows`: Desactiva las marcas de neumáticos permanentes en el suelo y simplifica las sombras dinámicas de los karts.
- `Simplify Heavy Effects & Smoke`: Reduce la densidad de partículas en las explosiones de cajas y el humo de los tubos de escape al usar turbos.
- `Simplify Animals Fur`: Reemplaza el pesado sombreador de pelaje dinámico de Crash, Coco, Tiny, etc., por texturas estáticas tradicionales que ahorran toneladas de VRAM.
- `Single Channel Audio`: Mezcla el audio en un canal monoaural para reducir el estrés de procesamiento en la CPU.

## ⚙️ Configuración Recomendada (Estilo Port de PC, Requiere una PC Algo potente)
Para exprimir este pack al máximo y lograr un acabado visual espectacular, aplica estos ajustes en tu emulador:
1. **Gráficos:** Activa un parche de 60 FPS junto con nuestro pack de optimización.
2. **Resolución:** Si tienes una GPU dedicada (como una GTX 1650 o superior), sube el escalado de resolución a **1.5x (1620p en modo Portátil)**. El juego se verá increíblemente nítido.
3. **Audio Fix:** Si notas chasquidos en el sonido al jugar a 60 FPS, ve a las configuraciones de Audio del emulador, cambia el motor a **SDL2** y aumenta el búfer de audio a **100 ms** para corregir la sincronización del motor.
4. **Contenido:** Debido a que las Boxes (*Pit Stop*) requieren conexión a servidores oficiales, se recomienda encarecidamente instalar un *Save Game al 100%* en la carpeta de usuario para desbloquear todos los personajes (como Spyro o Nina) y las skins desde el inicio.

## ⚠️ Nota
Este paquete ha sido testeado rigurosamente logrando 60 FPS blindados sin caídas. Si encuentras algún inconveniente con futuras revisiones, eres libre de abrir un Issue en este repositorio.

** Configuraciones del emulador (Eden, aunque tambien funciona en Yuzu, Ryujinx Y Asi)

**Sistema:** Si tienes PC Patata (Gama Baja) Dejalo en Handheld (Portatil) que reduce la resolucion y detalles pero que ganas muchos FPS, y en Docked (Sobremesa) para las PC Mas potentes, que tiene mayor detalle y resolucion, pero que consume mas, y activa "Synchronize Core Speed"
**CPU:" Dejalo en Unsafe si quieres maximos FPS (Solo que da mas Bugs visuales) Dejalo en Acurrate si quieres la menor cantidad de errores (Pero que consume mas) y Auto si no sabes que hacer
**Graficos:** La API dejala en Vulkan si o si, y si no te inicia el juego o se ve en negro dejalo en OpenGL (Pero de manera normal, Vulkan) En la resolucion, es recomendable dejarlo en 1x para abajo (Que en 1x es 720p en portatil y 1080p en sobremesa) Y Subela si tienes una PC Mas potente (Recomendado 1.5 o 1.25) En VSync dejalo en FIFO (Activado) y en Windows Adapting Filter dejalo en Bilinear para las PC Patata (Gama Baja) y AMD Super Resolution para PC Un poco mas potentes (:
**Graficos Avanzados:** En GPU Mode, dejalo en Fast si quieres maximos FPS, y Acurrate para la menor cantidad de errores visuales (Si quieres mi configuracion exacta, dejalo en Acurrate, aunque si te faltan FPS Dejalo en Fast) En Anisotropic Filter recomiendo dejarlo en 2x, 4x o Predeterminado (Si lo subes mas, sera mejor pero consumira mas) en ASTC Recompression Method recomiendo dejarlo en BC3 Y BC1, No cambiara nada y suma muchisimos FPS, Activa "Force Maximus Clocks" (Solo en Vulkan) Y Sync To Framerate to Videoplayback 
**Extensiones Graficas:** Activa "Fix Bloom Effects" y "Enable Asynchronous Shader Compilation"



---
