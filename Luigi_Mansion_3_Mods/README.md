# 🔦 Project #14: Luigi's Mansion 3 (v1.4.0 + DLC)
> **Status:** `OPTIMIZED` | **Performance:** `25-30 FPS Stable` | **Engine:** `Grip Engine`

This project represents the second-to-last stage of the repository (**14/15**). The optimization focuses on removing volumetric load and aggressive post-processing to allow smooth gameplay on mid-range hardware (GTX 1650), while maintaining the high visual fidelity of the GADU Hotel.

---

### 🔬 The Ghost-Hunting Matrix

| Module | Technical Optimization | System Impact |
| :--- | :--- | :--- |
| 👁️ **Focus** | `Disable Dyn. Res. & DoF` | **Sharpness:** 100% Native (No blur) |
| ✨ **Lighting** | `Disable Bloom & Lens Flare` | **Stability:** Lower load on GPU shaders |
| 🌫️ **Atmosphere** | `Disable Fog (Volumetric)` | **FPS:** Massive gain in hallways and lobbies |
| 👻 **Entities** | `Simplify Ghost Textures` | **VRAM:** Eliminates micro-stutters |
| 💧 **Physics** | `Simplify Water` | **GPU:** Smooth performance in sewer levels |
| 🔒 **Synchronization** | `30 FPS Stable Lock` | **Frame-Pacing:** 33.3ms - 40ms (No lag) |

---

### 🛠️ Laboratory Configuration (Eden Emulator)

To replicate the optimization results of the Scientific Sanctuary:

* **Graphics Backend:** `Vulkan` (Critical for light management).
* **Resolution Scale:** `1x (720p/1080p)`.
* **Anti-Aliasing:** `None` (Native sharpness is superior to FXAA).
* **Anisotropic Filtering:** `16x` (Maximum texture detail).
* **Disk Shader Cache:** `Enabled` (Prevents stutter when entering new areas).

---

### 🧪 Lead Engineer's Note
"Luigi's Mansion 3 is the ultimate 'benchmark' for this repository. By disabling volumetric fog and locking the framerate, we achieved a cinematic experience with a constant 25–30 FPS. The resulting image is cleaner than the original console version, allowing Next Level Games' artistic design to shine on an i3 + GTX 1650."
