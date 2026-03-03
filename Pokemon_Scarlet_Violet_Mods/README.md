# 🛡️ Scientific Sanctuary: Project #17 - Paldea Stable Edition
**Target Game:** Pokémon Scarlet & Violet (Gen 9)  
**Target Version:** 1.0.0 (Base Game)  
**Philosophy:** Optimization for Mid-Range, Low-End & Integrated Graphics (GTX 1650 / i3 / Handhelds).

---

## 🚀 Overview
Pokémon Scarlet and Violet are notorious for their poor optimization. **Project #18** is a surgical modification pack designed to remove engine-level bottlenecks, stabilize frametimes, and provide a crisp visual experience without the "blur" that plagues the original game.

> "We don't add heavy effects; we remove what's broken to let your hardware breathe."

---

## 🛠️ Included Optimizations
This pack is divided into individual `.pchtxt` files to avoid crashes and allow customization:

| Mod Name | Function | Hardware Benefit |
| :--- | :--- | :--- |
| **Disable FXAA** | Removes native blur. | Maximum Clarity. |
| **Disable DynRes** | Keeps resolution fixed. | Stabilizes Frame-pacing. |
| **Simplify Water** | Optimized shaders for lakes/oceans. | +5-8 FPS in water areas. |
| **Low Shadows** | Reduces shadow complexity. | Lowers CPU usage. |
| **No Floor Marks** | Removes footprints/marks. | Frees up VRAM. |
| **Simplify Textures**| Lightens Pokémon shaders. | Prevents stuttering. |

---

## 📋 Installation & Compatibility

1. **Version:** Strictly for **v1.0.0**.
2. **Emulator:** Compatible with **Ryujinx** and **Yuzu**.
3. **Setup:** - Right-click the game in your emulator.
   - Select `Open Mods Directory`.
   - Paste the desired `.pchtxt` files there.

### 🔄 Pokemon Violet (Púrpura) Compatibility
If you are playing the **Violet** version, you must change the first line of each file to its corresponding ID:

* **Scarlet ID:** `@nsobid-679E1431CA8308D07212E571F15317E3D8523A9E`
* **Violet ID:** `@nsobid-D8DBB44503C350280D3BA8FE65CD5534FC897D86`

---

## ⚠️ Known Issues
- **Z-Fighting (Flickering):** Some objects may flicker due to texture compression (especially if using **BC1** recompression). This is a trade-off for 30 FPS stability on 4GB VRAM cards like the **GTX 1650**.
- **First Cinematic:** May stutter while caching shaders.

---

## ⭐ Credits
Developed by **The Scientific Sanctuary Team**.  
*Tested on Intel i3 + GTX 1650 + 16GB RAM.* **Special thanks to "Diarrea" (The Quaxly) for the test runs.**
