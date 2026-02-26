# 🌟 Kirby Star Allies: Ultra Clarity & Solid Performance (v4.0.0)

¡Bienvenido al **Kirby's Scientific Sanctuary**! Si tienes un hardware de gama media como un **i3 + GTX 1650**, este es el lugar donde el juego deja de ser una "mancha borrosa" para convertirse en una experiencia nítida y fluida.

> **Filosofía del Laboratorio:** Rendimiento por encima de calidad. Si no nos da 30 FPS estables, no entra en el santuario
Antes (Borroso Y Muy Inestable)

<img width="1920" height="1080" alt="Captura de pantalla (136)" src="https://github.com/user-attachments/assets/278b9c3c-911f-48f8-9120-c1aebb665914" />

---

Despues (Mayores Fps, Estabilidad Y Mayor Nitidez)

<img width="1920" height="1080" alt="Captura de pantalla (137)" src="https://github.com/user-attachments/assets/fe46a350-2b12-4371-b49c-e15789b52d00" />

---
## 🧪 Los Experimentos (Mods Incluidos)

He seleccionado y testeado esta combinación maestra para obtener el mejor equilibrio visual y técnico:

### ⚡ Rendimiento "Rock Solid"
* **30 FPS Rock Solid:** Elimina las caídas de frames y mantiene el juego pegado a 30 FPS para una fluidez constante en CPUs modestas.
* **Fix Friendship Abilities Lag:** Optimiza el procesado de partículas cuando usas habilidades con amigos, evitando tirones en combate.
* **Disable Dynamic Resolution:** Evita que el juego se pixele solo; mantenemos la resolución fija para mayor nitidez.

### 💎 Claridad Visual (Adiós Borrosidad)
* **Remove Bluryness & Ultra Clarity:** Elimina el filtro borroso original de Switch para una imagen limpia de PC.
* **Disable DoF & Fog:** Quita el desenfoque de fondo y la neblina, revelando la verdadera geometría del juego.
* **Disable Bloom:** Reduce el resplandor excesivo para que los colores de Kirby sean más sólidos y definidos.

### 🎨 Toque Estético
* **High Quality Shadows:** Como nuestra GTX 1650 puede con ello, mantenemos sombras definidas para que el juego no pierda profundidad.
* **No Outlines:** (Opcional) Elimina los bordes negros de los personajes para un look más moderno y suave.

** 🎈Configuracion Maestra Ryujinx

**Graphics:** * **Backend:** Vulkan (Obligatorio para Nvidia/AMD).
   * **Resolution Scale:** 1x (Native). No subas a 2x si quieres mantener los 30 FPS estables.
2. **System:**
   * **Expand DRAM size to 4GB:** Ayuda a que los shaders carguen mejor.
3. **Add-ons:**
   * Haz clic derecho en el juego -> *Open Mods Directory* y pega aquí la carpeta de este repositorio.
--- 
## 🔧 Configuración Maestra De Yuzu

**Sistema:** En Memory Layout Poner En 4GB VRAM, Y Si Tienes Graficas Integradas Pon El Juego en modo portatil (Cambiar de Docked A Hadheld)
**Graficos:** Poner Vulkan Obligatoriamente (Sobretodo En Graficas Integradas) > [!WARNING] En NVDEC Emulation Pon En CPU Video Decoding (Si No EL Juego Ira Mal) En Resolution Pon Recomendamos Poner 1x para abajo (Ya que si subes el escalado a mas de 2x el juego se bugueara)
Y En Anti-Aliasing Poner En None (Obligatorio Para mas nitidez y Fps) Y En Adapting Filter Pon En Bilinear para mas rendimiento y AMD Super Resolution Para mas calidad (Pero reduce el rendimiento)
**Graficos Avanzados:** Pon Obligatoriamente En Normal (Si no el juego no va ir al 100%) En Anisotropic Filter Pon en Default O Subelo Para mas calidad (Pero eso ultimo reduce el rendimiento) En ASTC Recompression Method Pon En BC1 Para Mayor Rendimiento (Casi no afecta en lo visual
**Varias Opciones:** Aciva El Force Maximus Clocks, (Sobre Todo en graficas integradas) Use Asynchronouis Shader Building ACTIVADO, (Muy Importante) Y Aciva El Sync to framerate video playback
