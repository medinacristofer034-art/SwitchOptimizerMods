# Crash Bandicoot 4: It's About Time - Maximum Performance Pack

Este repositorio contiene una suite modular de parches de optimización para **Crash Bandicoot 4: It's About Time** (v1.2). Dado que este título utiliza el motor **Unreal Engine 4**, la carga gráfica puede ser muy exigente en emulación. Este pack está diseñado específicamente para aliviar la presión sobre la GPU, permitiendo que el juego sea ejecutable en PCs con gráficas integradas y dispositivos móviles (Android).

## 🚀 Filosofía del Pack
El enfoque principal es la **eliminación de procesos pesados y la simplificación de shaders**. Estos parches permiten escalar la experiencia desde un modo "Potato/Ultra-Light" para máxima estabilidad, hasta configuraciones más equilibradas.

## 🛠️ Módulos de Optimización (.pchtxt)
Puedes elegir y combinar los siguientes parches individuales:

### 1. Post-Procesado y Nitidez
- `Disable Dynamic Resolution`: Mantiene una resolución constante y nítida.
- `Disable Bloom Effects`: Elimina el brillo excesivo para mejorar la visibilidad.
- `Disable DoF & Motion Blur`: Elimina el desenfoque de cámara y lente, mejorando la respuesta visual.
- `Disable FXAA`: Desactiva el suavizado de bordes para mayor definición.

### 2. Geometría y Entorno
- `Low Quality Shadows`: Reduce la complejidad de las sombras dinámicas.
- `Anti Vertex Explosion`: Previene bugs gráficos y estiramientos de polígonos durante la carga de assets.

### 3. Simplificación de Efectos (Optimización UE4)
- `Simplify Heavy Effects & Reflex`: Aligera la carga en escenas complejas y superficies reflectantes.
- `Simplify Particle Effects`: Optimiza drásticamente elementos como fuego, agua, slime y explosiones.
- `Simplify Hair & Fur`: Reduce la carga geométrica del pelaje de los personajes (mejora clave para Android).

### 4. Audio y Estabilidad
- `Single Channel Audio`: Optimiza el procesamiento del audio para prevenir desincronizaciones.

## ⚙️ Recomendaciones de Configuración
Para obtener la mejor experiencia en hardware limitado o emulación móvil:

*   **API:** **Vulkan** es indispensable para la gestión de memoria del Unreal Engine 4.
*   **Modo GPU:** Configúralo en **Fast** para evitar latencia.
*   **Gestión de Recursos:** Si el emulador cierra inesperadamente al iniciar, activa primero `Anti Vertex Explosion` y `Low Quality Shadows`.
