# 🦔 Project #12: Sonic Superstars
> **Status:** `STABLE` | **Version:** `1.0.0` | **Optimized by:** `The Scientific Sanctuary`

¡Velocidad sónica sin compromisos! Este paquete está diseñado para la versión base (v1.0.0), eliminando los efectos de post-procesado que causan latencia y caídas de frames en hardware de gama media.

---

### 🧬 **The Hedgehog Performance Matrix**

| Módulo | Optimización Técnica | Impacto en Sistema |
| :--- | :--- | :--- |
| 👁️ **Imagen** | `Disable Dyn. Res. & FXAA` | **Nitidez:** 100% Nativa |
| 🌪️ **Atmósfera** | `No Bloom / No Fog` | **Claridad:** Colores más puros |
| 🏃 **Fluidez** | `Disable DoF` | **Estabilidad:** 60 FPS rocosos |
| 🌑 **Sombreado** | `Low Quality Shadows` | **GPU:** Ahorro de ciclos crítico |
| 🌊 **Entorno** | `Simplify Water Shaders` | **VRAM:** Mejoras en zonas de agua |
| 💥 **Efectos** | `Disable Heavy Effects` | **Frames:** Sin tirones por partículas |

---

### 🛠️ **Configuración del Laboratorio (Setup)**

Para corregir errores visuales en las texturas de los personajes y el entorno, aplica estos ajustes:

* **API:** `Vulkan`
* **ASTC Recompression:** `Uncompressed` (Soluciona los puntos negros en texturas).
* **Decode ASTC Textures Asynchronously:** `ON`
* **Shader Cache:** Limpiar antes de iniciar si los colores se ven extraños.

---

### 🧪 **Nota del Ingeniero Principal**
"Con el Proyecto #12, el objetivo era la claridad absoluta. Al desactivar el Bloom y la Niebla, los niveles de Sonic Superstars recuperan ese look vibrante de los juegos clásicos, pero con el rendimiento de un PC moderno. ¡60 FPS garantizados en i3 + GTX 1650!"
