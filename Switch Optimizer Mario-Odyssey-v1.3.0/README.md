🍄 Optimización: Super Mario Odyssey (v1.3.0)

Este pack aplica el **Nivel Patata** para eliminar el lag en zonas exigentes como New Donk City.

## 📊 Comparativa de Rendimiento

Antes ( Escenario Borroso, Inestabilidad)

<img width="1920" height="1080" alt="Captura de pantalla (122)" src="https://github.com/user-attachments/assets/3e0e1bde-9980-4afd-b266-eb30fdf67e33" />

---
Despues Con Los Mods (Mayores Fps Y Estabilidad, Imagen Nitida Y 720p Mejorados)

<img width="1920" height="1080" alt="Captura de pantalla (123)" src="https://github.com/user-attachments/assets/1cc83efb-3905-4403-aee5-fb7c09d67315" />

---
## ⚙️ Configuración Maestra (Ryujinx Canary)
Para estos resultados en un **i3 + GTX 1650**, usa:
* **Sistema:** Tamaño DRAM en **4GB**.
* **Gráficos:** Backend **Vulkan** + Filtro **Bilineal**.
* **Procesador:** Administrador de Memoria en **Host Sin Verificación**.
---
## ⚙️ Configuración Maestra (Yuzu Early Acess Y Parecidos)
* **Sistema:** Memory Layout En 4GB, Y Si Tienes Graficas Integradas Ponlo En Handheld
* **CPU:** La Mejor Opcion Es Auto
* **Graficos:** Api Vulkan Obligatoriamente, El Vsync Activado, La Resolucion Puede Ser La Que Quieras Pero Recomendamos Poner La Escala En 1x Para Abajo (Como 0.75 O 0.5), En Adapting Filter Pon Bilinear Para Mayor Estabilidad Y AMD Super Resolution Para Mas Calidad Visual
* Y En Anti-Aliasing Poner En None (Muy Importante Ponerlo Asi)
* **Graficos Avanzados:** En Acurracy Level Pon En Normal Muy Importante, En Anisotropic Filter Poner En Default O Subirlo Para Mayor Calidad (Pero Quita Fps Y Rendimiento) En ASTC Recompression Method Poner En BC1 (Aumenta Muchisimo Los Fps)
* Poner Las Siguientes Opciones Muy Importante: Force Maximum Clock ACTIVADO, Use Asynchronous Shader Building ACTIVADO, Y Sync to framerate of video playback ACTIVADO
