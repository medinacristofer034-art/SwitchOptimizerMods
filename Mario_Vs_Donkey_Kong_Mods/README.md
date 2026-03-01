# 🧩 Proyecto #13: Mario vs. Donkey Kong (v1.0.1)
> **Status:** `ULTRA-SHARP` | **Version:** `1.0.1` | **Engine:** `Toy-Box Engine`

Este proyecto se enfoca en la eliminación de los filtros de post-procesado agresivos (Blur/DoF) para lograr una nitidez nativa superior a la de la consola original. Optimizado para mantener 60 FPS estables en una GTX 1650 mediante la simplificación de efectos de iluminación y texturas de pelaje.

---

### 🔬 The Toy-Factory Matrix

| Módulo | Optimización Técnica | Impacto en Sistema |
| :--- | :--- | :--- |
| 👁️ **Foco** | `Disable Dyn. Res. & DoF` | **Nitidez:** Imagen 100% cristalina |
| ✨ **Iluminación** | `Disable Bloom & Fog` | **Claridad:** Colores sólidos sin neblina |
| 🧹 **Suavizado** | `Disable FXAA` | **Input Lag:** Reducción de latencia de procesado |
| 🦍 **Texturas** | `Simplify DK Fur` | **CPU:** Menor carga física en el pelaje de DK |
| 🌊 **Líquidos** | `Simplify Water & Lava` | **GPU:** Estabilidad en niveles con efectos fluidos |
| 🧼 **Superficies** | `No Floor Marks` | **VRAM:** Optimización de memoria de texturas |
| 🌑 **Sombreado** | `Low Quality Shadows` | **FPS:** Ganancia de estabilidad en zonas densas |

---

### 🛠️ Configuración del Laboratorio (Eden Emulator)

Para replicar los resultados de la captura de pantalla oficial:

* **Graphics Backend:** `Vulkan` (Indispensable para la v1.0.1).
* **Resolution Scale:** `1x (720p/1080p)`.
* **Anti-Aliasing:** `None` (La nitidez nativa elimina la necesidad de AA).
* **Anisotropic Filtering:** `16x` (Texturas de juguetes con máximo detalle).
* **Vsync:** `ON` (Para una sincronía perfecta de 60 FPS).

---

### 🧪 Nota del Ingeniero Principal
"El Proyecto #14 transforma el look 'borroso' del remake en una estética de juguetes reales y definidos. Al desactivar el Bloom y simplificar el pelaje de Donkey Kong, el juego recupera la esencia vibrante del original de GBA con la potencia de una arquitectura moderna, eliminando cualquier rastro de neblina innecesaria en la GTX 1650."
