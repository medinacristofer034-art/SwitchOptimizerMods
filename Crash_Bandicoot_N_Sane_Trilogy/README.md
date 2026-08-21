# Crash Bandicoot N. Sane Trilogy: Maximum Performance Pack

Este repositorio contiene una suite modular de parches de optimización para **Crash Bandicoot N. Sane Trilogy** (v1.0.0). Diseñado para permitir una experiencia jugable fluida tanto en PCs con gráficas integradas como en dispositivos Android, eliminando efectos de post-procesado pesados y optimizando la geometría compleja.

## 🚀 Filosofía del Pack
Este pack se centra en la **optimización técnica y la reducción de carga gráfica**. Los parches están completamente separados para que puedas configurar el rendimiento exactamente a la medida de tu dispositivo, eliminando lo innecesario sin sacrificar la esencia del juego.

## 🛠️ Módulos de Optimización (.pchtxt)
Puedes elegir y combinar los siguientes parches individuales:

### 1. Resolución y Post-Procesado
- `Disable Dynamic Resolution`: Bloquea la resolución para evitar caídas de calidad.
- `Disable Bloom Effects`: Elimina el brillo artificial para una imagen más nítida.
- `Disable Depth of Field (DoF)`: Desactiva el desenfoque de lente en segundo plano.
- `Disable Fog`: Limpia la atmósfera en los niveles.
- `Disable FXAA`: Desactiva el suavizado nativo para mayor definición.
- `Disable Motion Blur`: Esencial para mantener la claridad en los giros rápidos de Crash.
- `Disable Lens Flare`: Elimina los destellos de luz directa.

### 2. Entorno y Geometría
- `Disable Floor Marks`: Previene la acumulación de marcas en el suelo para ahorrar recursos.
- `Low Quality Shadows`: Reduce la resolución de sombras dinámicas para aliviar la GPU.

### 3. Simplificación de Efectos (Rendimiento Crítico)
- `Simplify Illumination`: Ajuste profundo de la iluminación dinámica del motor.
- `Simplify Animal's Fur`: Reduce la complejidad del sistema de pelaje de Crash (mejora masiva en rendimiento).
- `Simplify Grass, Fire & Ice`: Aligera los elementos ambientales más pesados.
- `Simplify Clime Effects`: Optimiza efectos climáticos y ambientales.
- `Simplify Heavy Effects`: Reduce la carga en eventos gráficos masivos.
- `Simplify Reflex`: Optimiza superficies reflectantes.

### 4. Audio
- `Single Channel Audio`: Optimiza el flujo sonoro para evitar micro-cortes en hardware limitado.

## ⚙️ Recomendaciones de Configuración
Para obtener el mejor rendimiento en hardware de gama baja, Android o gráficas integradas:

*   **API:** **Vulkan** es obligatorio para una compilación de shaders eficiente.
*   **Modo GPU:** Configúralo en **Fast** para asegurar estabilidad en dispositivos con VRAM compartida.
*   **Estrategia de Uso:** Si el juego presenta tirones, prioriza la activación de `Simplify Animal's Fur`, `Simplify Heavy Effects` y `Low Quality Shadows`.

---
*¡Lleva a Crash Bandicoot a donde sea con el motor optimizado al límite!*
