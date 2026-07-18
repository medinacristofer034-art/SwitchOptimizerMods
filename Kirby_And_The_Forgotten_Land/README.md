# Kirby and the Forgotten Land: Maximum Performance Pack

Este repositorio contiene una suite modular de optimización diseñada para **Kirby and the Forgotten Land** (v1.0.0). El objetivo principal es eliminar los errores gráficos comunes en emuladores y desbloquear el máximo potencial de rendimiento, permitiendo que el juego se mantenga fluido incluso bajo cargas pesadas de shaders.

## 🚀 Filosofía del Pack
Este pack se centra exclusivamente en **optimizar el motor gráfico**. No incluye modificaciones de gameplay, skins o animaciones; su propósito es ofrecer una base técnica sólida y estable. Los mods externos (skins, cambios de dificultad, animaciones personalizadas o parches de 60 FPS) son totalmente compatibles y se recomienda obtenerlos a través de la comunidad de [GameBanana](https://gamebanana.com/). O Otros repositorios de GitHub como [theboy181](https://github.com/theboy181/switch-ptchtxt-mods).

## 🛠️ Módulos de Optimización (.pchtxt)
Todos los parches están separados para que elijas solo los que necesites:

- `Dynamic FPS & Delta Time Fix`: Imprescindible para evitar el efecto de "cámara lenta" cuando el juego baja de su objetivo de FPS.
- `Anti-Vertex Explosion`: Elimina los fallos geométricos donde los objetos se estiran o explotan visualmente.
- `Anti-Flickers (LOD Stability)`: Estabiliza los objetos lejanos para evitar el parpadeo de texturas.
- `Simplify Reflex`: Reduce la carga de cálculo en superficies reflectantes y agua.
- `Simplify Character Textures`: Optimiza la resolución de las texturas de los personajes sin perder calidad visual notable.
- `Simplify FX & Particle`: Aligera drásticamente la carga de efectos visuales pesados durante explosiones o combates intensos.
- `Disable Lens Flare`: Desactiva los destellos de lente innecesarios, ganando ciclos de GPU.
- `No Floor Marks`: Elimina las marcas temporales en el suelo, limpiando la escena.
- `Single Channel Audio`: Reduce el uso de CPU forzando la mezcla de audio a un único canal.
-  `Disable Dynamic Resolution:` Desactiva la resolucion dinamica para que no baje la resolucion que haz puesto, mejora la estabilidad y se siente menos brusco o pesado al tener muchos efectos de pantalla
-   `Disable Post-Procesing:` Desactiva el Post-Procesado del juego para que se vea mas nitido y consuma mucho menos, desactiva el Fog, DoF, Bloom Y Motion Blur

## ⚙️ Recomendaciones de Configuración
Para obtener la experiencia definitiva, combina este pack con los siguientes ajustes en tu emulador:

*   **API:** Usa **Vulkan** para una mejor gestión de shaders.
*   **Modo GPU:** Si buscas estabilidad absoluta, usa **Accurate**. Si tu prioridad es exprimir cada FPS posible, puedes cambiarlo a **Fast**.
*   **Shaders:** Se recomienda tener activada la compilación de shaders asíncronos para evitar tirones durante la carga de nuevos efectos.
*   **Compatibilidad:** Este pack es compatible con la mayoría de mods de GameBanana (60 FPS, Skins, Dificultad, etc.). Si instalas un mod de 60 FPS, asegúrate de que el `Dynamic FPS` esté activo para mantener la coherencia del tiempo en el juego.

---
*¡Disfruta del viaje al Mundo Olvidado con el mejor rendimiento técnico posible!*
