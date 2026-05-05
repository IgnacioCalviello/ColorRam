# Chromata — Explorador de Paletas 🎨

Chromata (también conocido como ColorsRam) es una aplicación web rápida e intuitiva para generar paletas de colores hermosas al instante. Diseñada con una interfaz minimalista, permite a los desarrolladores y diseñadores explorar, modificar y exportar esquemas de color de manera eficiente.

## ✨ Características Principales

* **Generación Instantánea:** Presiona la barra espaciadora para crear una nueva paleta de colores al instante.
* **Modos de Armonía:** Elige entre múltiples algoritmos de coloración, incluyendo Libre, Análoga, Complementaria, Triádica y Monocromática.
* **Control Total:** Añade hasta 8 colores o reduce la paleta a 2. Bloquea colores individuales para mantenerlos mientras generas el resto.
* **Sistema de Historial y Deshacer:** Navega por las paletas generadas anteriormente o usa `Ctrl+Z` para deshacer tu último cambio.
* **Exportación Fácil:** Exporta tu paleta terminada en múltiples formatos listos para usar:
  * Códigos HEX
  * Valores HSL
  * Variables CSS
  * Configuración para Tailwind CSS
* **Diseño Responsivo:** Funciona perfectamente tanto en dispositivos de escritorio como móviles.

## 🚀 Tecnologías Utilizadas

Este proyecto está construido íntegramente con tecnologías web estándar (Vanilla), sin dependencias externas complejas:

* **HTML5:** Estructura semántica.
* **CSS3:** Variables nativas (`:root`), Flexbox, transiciones suaves y animaciones.
* **JavaScript (ES6):** Lógica de generación de colores (conversión HSL a HEX), manipulación del DOM y gestión del portapapeles.
* **Google Fonts:** Uso de *Instrument Sans*, *Instrument Serif* y *DM Mono* para la tipografía.

## 🛠️ Cómo usar el proyecto

Al ser un proyecto estático, no requiere un proceso de instalación complejo ni servidores de desarrollo:

1. Clona o descarga este repositorio en tu computadora.
2. Abre la carpeta del proyecto.
3. Haz doble clic en el archivo `index.html` para abrirlo directamente en tu navegador web favorito.
4. ¡Empieza a presionar la barra espaciadora para generar colores!

## ⌨️ Atajos de Teclado

* **Espacio:** Generar una nueva paleta (para los colores no bloqueados).
* **Ctrl + Z / Cmd + Z:** Deshacer la última acción.
* **Enter:** (Con un color seleccionado) Generar una nueva gama basada en el color enfocado.