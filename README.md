# Chromata — Explorador de Paletas 🎨

Chromata (también conocido como ColorsRam) es una aplicación web rápida e intuitiva para generar paletas de colores hermosas al instante[cite: 2]. Diseñada con una interfaz minimalista, permite a los desarrolladores y diseñadores explorar, modificar y exportar esquemas de color de manera eficiente[cite: 2].

## ✨ Características Principales

* **Generación Instantánea:** Presiona la barra espaciadora para crear una nueva paleta de colores al instante[cite: 2].
* **Modos de Armonía:** Elige entre múltiples algoritmos de coloración, incluyendo Libre, Análoga, Complementaria, Triádica y Monocromática[cite: 2].
* **Control Total:** Añade hasta 8 colores o reduce la paleta a 2[cite: 2]. Bloquea colores individuales para mantenerlos mientras generas el resto[cite: 2].
* **Sistema de Historial y Deshacer:** Navega por las paletas generadas anteriormente o usa `Ctrl+Z` para deshacer tu último cambio[cite: 2].
* **Exportación Fácil:** Exporta tu paleta terminada en múltiples formatos listos para usar[cite: 2]:
  * Códigos HEX[cite: 2]
  * Valores HSL[cite: 2]
  * Variables CSS[cite: 2]
  * Configuración para Tailwind CSS[cite: 2]
* **Diseño Responsivo:** Funciona perfectamente tanto en dispositivos de escritorio como móviles[cite: 2].

## 📁 Estructura del Proyecto

El código está organizado para ser fácil de mantener:
* `index.html`: Contiene la estructura principal de la página, la lógica de generación de colores (JavaScript) y enlaza a nuestra hoja de estilos[cite: 1].
* `styles.css`: Contiene todos los estilos visuales separados para mantener el código ordenado y modular[cite: 1].

## 🚀 Tecnologías Utilizadas

Este proyecto está construido íntegramente con tecnologías web estándar (Vanilla), sin dependencias externas complejas[cite: 2]:

* **HTML5:** Estructura semántica[cite: 2].
* **CSS3:** Variables nativas (`:root`), Flexbox, transiciones suaves y animaciones[cite: 2].
* **JavaScript (ES6):** Lógica de generación de colores (conversión HSL a HEX), manipulación del DOM y gestión del portapapeles[cite: 2].
* **Google Fonts:** Uso de *Instrument Sans*, *Instrument Serif* y *DM Mono* para la tipografía[cite: 2].

## 🛠️ Cómo usar el proyecto

Al ser un proyecto estático, no requiere un proceso de instalación complejo ni servidores de desarrollo[cite: 2]:

1. Clona o descarga este repositorio en tu computadora[cite: 2].
2. Abre la carpeta del proyecto[cite: 2]. Asegúrate de que los archivos `index.html` y `styles.css` estén juntos en la misma ubicación[cite: 1].
3. Haz doble clic en el archivo `index.html` para abrirlo directamente en tu navegador web favorito[cite: 2].
4. ¡Empieza a presionar la barra espaciadora para generar colores![cite: 2]

## ⌨️ Atajos de Teclado

* **Espacio:** Generar una nueva paleta (para los colores no bloqueados)[cite: 2].
* **Ctrl + Z / Cmd + Z:** Deshacer la última acción[cite: 2].
* **Enter:** (Con un color seleccionado) Generar una nueva gama basada en el color enfocado[cite: 2].