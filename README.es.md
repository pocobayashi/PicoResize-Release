# ⚡ PicoResize

[日本語](README.md) | [English](README.en.md) | [简体中文](README.zh-CN.md) | [繁體中文](README.zh-TW.md) | [한국어](README.ko.md) | [Español](README.es.md) | [Deutsch](README.de.md) | [Français](README.fr.md)

---

**PicoResize** es una aplicación de escritorio para Windows de alto rendimiento diseñada para el procesamiento por lotes de imágenes (JPG, PNG, WebP, BMP, TIFF) y documentos PDF con **recorte automático de márgenes**, **ajuste inteligente de proporción** y **compresión a un tamaño objetivo (MB)** en un entorno local 100% seguro y sin conexión.

---

## 🌟 Características principales

1. **Recorte automático de márgenes blancos (Auto Trim)**
   - Detecta y elimina automáticamente los bordes y márgenes blancos innecesarios de fotos, imágenes escaneadas y páginas PDF.
2. **Redimensionamiento inteligente según orientación (Preservando la relación de aspecto)**
   - Ajusta las imágenes al cuadro especificado (por ejemplo, `[ 640 ] × [ 480 ]`):
     - **Imágenes horizontales (Ancho ≥ Alto)**: Se ajusta a Ancho × Alto = `640 × 480` manteniendo la proporción.
     - **Imágenes verticales (Alto > Ancho)**: Se ajusta a Alto × Ancho = `640 × 480` (Ancho 480 × Alto 640) con rotación automática de orientación.
3. **Compresión automática a tamaño de archivo objetivo (MB)**
   - Ajusta automáticamente la calidad mediante búsqueda binaria para garantizar que los archivos queden por debajo del límite deseado (ej. `0.5` MB) minimizando la pérdida visual.
4. **Renombrado automático de archivos duplicados**
   - Si ya existe un archivo con el mismo nombre en la carpeta de destino, añade automáticamente `(2)`, `(3)`, etc., evitando sobreescrituras accidentales.
5. **Procesamiento conjunto y fluido de imágenes y PDF**
   - Arrastre y suelte archivos PDF (primera página rasterizada a 300 DPI) e imágenes de diversos formatos en la misma cola.
6. **Consumo de memoria ultrabajo (Estable en 10–20 MB)**
   - Utiliza recorte de conjunto de trabajo Win32, virtualización de interfaz y recolección de memoria inactiva para operar en apenas ~10 MB.
7. **Localización completa en 8 idiomas**
   - 🌐 Compatible con japonés, inglés, chino simplificado, chino tradicional, coreano, español, alemán y francés con cambio instantáneo en tiempo real.
8. **Actualizaciones automáticas con Velopack**
   - Integración nativa con Velopack para actualizaciones diferenciales con un solo clic.

---

## 🖥️ Requisitos del sistema
- **Sistema operativo**: Windows 10 (versión 2004 o superior) / Windows 11 (x64)
- **Entorno de ejecución**: Autónomo / Self-contained (no requiere instalar .NET por separado)

---

## 🚀 Guía de inicio rápido
1. Ajuste las dimensiones de proporción (`Ancho × Alto`), el tamaño objetivo en MB y el formato de salida (`JPEG / PNG / WebP`).
2. Arrastre y suelte sus imágenes o archivos PDF en el área central (o use el botón "Añadir archivos").
3. Haga clic en "🚀 Redimensionar y guardar" y elija la carpeta de destino.
4. Al finalizar, aparecerá un diálogo de confirmación con la opción de abrir la carpeta de destino con un clic.

---

## 📄 Licencia
Licencia MIT
