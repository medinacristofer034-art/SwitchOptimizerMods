# 🔦 Proyecto #14: Luigi's Mansion 3 (v1.4.0 + DLC)
> **Status:** `OPTIMIZED` | **Performance:** `25-30 FPS Stable` | **Engine:** `Grip Engine`

Este proyecto representa el penúltimo escalón del repositorio (**14/15**). La optimización se centra en la eliminación de la carga volumétrica y el post-procesado agresivo para permitir una jugabilidad fluida en hardware de gama media (GTX 1650), manteniendo la alta fidelidad visual del Hotel GADU.

---

### 🔬 The Ghost-Hunting Matrix

| Módulo | Optimización Técnica | Impacto en Sistema |
| :--- | :--- | :--- |
| 👁️ **Foco** | `Disable Dyn. Res. & DoF` | **Nitidez:** 100% Nativa (Sin borrosidad) |
| ✨ **Iluminación** | `Disable Bloom & Lens Flare` | **Estabilidad:** Menor carga en shaders de GPU |
| 🌫️ **Atmósfera** | `Disable Fog (Volumetric)` | **FPS:** Ganancia masiva en pasillos y vestíbulos |
| 👻 **Entidades** | `Simplify Ghost Textures` | **VRAM:** Eliminación de micro-tirones (Stutter) |
| 💧 **Físicas** | `Simplify Water` | **GPU:** Fluidez en niveles de alcantarillado |
| 🔒 **Sincronía** | `30 FPS Stable Lock` | **Frame-Pacing:** 33.3ms - 40ms (Sin lag) |

---

### 🛠️ Configuración del Laboratorio (Eden Emulator)

Para replicar los resultados de la optimización del Scientific Sanctuary:

* **Graphics Backend:** `Vulkan` (Crítico para la gestión de luces).
* **Resolution Scale:** `1x (720p/1080p)`.
* **Anti-Aliasing:** `None` (La nitidez nativa es superior al FXAA).
* **Anisotropic Filtering:** `16x` (Detalle máximo en texturas).
* **Disk Shader Cache:** `Enabled` (Evita tirones al entrar en nuevas áreas).

---

### 🧪 Nota del Ingeniero Principal
"Luigi's Mansion 3 es el 'benchmark' definitivo para este repositorio. Al desactivar la niebla volumétrica y fijar el framerate, hemos logrado una experiencia cinematográfica de 25-30 FPS constantes. La imagen resultante es más limpia que la versión original de consola, permitiendo que el diseño artístico de Next Level Games brille en un i3 + GTX 1650."
