# Mortal Kombat 1: Maximum Performance Pack (Switch Port Optimization)

Este repositorio contiene una suite modular de parches de optimización para **Mortal Kombat 1** (v1.29.0). Diseñado específicamente para aliviar la enorme carga gráfica de este port en emuladores, desactivando efectos pesados de post-procesado, corrigiendo bugs visuales y mejorando la estabilidad general del rendimiento.

## 🚀 Filosofía del Pack
Este pack se enfoca puramente en la **optimización extrema y la estabilidad del motor**. Los parches se encuentran totalmente separados para que puedas activar o desactivar cada modificación de forma independiente según las capacidades de tu equipo (ideal para exprimir hardware de gama media, gráficos integrados o dispositivos móviles).

## 🛠️ Módulos de Optimización (.pchtxt)
Puedes elegir y combinar los siguientes parches individuales:

### 1. Resolución y Post-Procesado
- `Disable Dynamic Resolution`: Mantiene la resolución fija sin caídas repentinas de calidad visual.
- `Disable Bloom Effects`: Elimina el brillo excesivo para un aspecto más limpio.
- `Disable Depth of Field (DoF)`: Remueve el efecto de desenfoque de lente en los escenarios y combates.
- `Disable Fog`: Limpia la atmósfera en los escenarios pesados.
- `Disable FXAA`: Desactiva el suavizado de bordes nativo para mayor nitidez de píxeles.
- `Disable Motion Blur`: Evita las estelas borrosas al girar la cámara o ejecutar movimientos rápidos.

### 2. Entorno y Estabilidad Visual
- `Disable Floor Marks`: Previene la acumulación innecesaria de marcas de impactos y pisadas en el suelo.
- `Anti Vertex Explosion`: Evita los errores gráficos críticos y estiramientos de polígonos ("texturas derretidas").
- `Static Stage Backgrounds`: Fija los elementos animados de fondo para aliviar la carga de la GPU.
- `Low Quality Shadows`: Reduce la resolución de las sombras dinámicas para liberar ciclos de procesamiento.

### 3. Simplificación de Efectos y Carga
- `Simplify Reflex`: Optimiza los cálculos de superficies reflectantes.
- `Simplify Heavy Effects`: Aligera la carga gráfica en fatalities y movimientos especiales masivos.
- `Simplify Hair & Fur`: Reduce la complejidad geométrica del cabello y pelaje de los personajes.
- `Simplify Fire, Ice, Slime, Smoke & Blood`: Aligera drásticamente los efectos de partículas pesadas (elementos icónicos del combate).

### 4. Rendimiento y Audio
- `Faster Loading Screens`: Optimiza los tiempos de carga en la medida de lo posible.
- `Single Channel Audio`: Optimiza el flujo de procesamiento de sonido para evitar micro-cortes.

## ⚙️ Recomendacion de Configuración
Para obtener la experiencia definitiva, combina este pack con las siguientes ajustes en tu emulador (como Yuzu/Ryujinx):

*   **API:** Utiliza **Vulkan** obligatoriamente para una mejor gestión de la caché de shaders y evitar cierres inesperados.

---
*¡Disfruta de las peleas con el motor completamente optimizado y libre de lastres visuales!*
