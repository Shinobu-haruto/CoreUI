# CoreUI v1.1 - Industrial HUD Environment  [Branding](https://github.com/Shinobu-haruto/CoreUI/blob/main/logo-full.svg)

[![License: MIT](https://img.shields.io/badge/License-MIT-00CCCC.svg)](LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Shinobu-haruto/CoreUI)](https://github.com/Shinobu-haruto/CoreUI/stargazers)
[![GTK4 Ready](https://img.shields.io/badge/GTK4-Compatible-00CCCC)](https://github.com/Shinobu-haruto/CoreUI)

![screenshot.png](https://github.com/Shinobu-haruto/CoreUI/blob/main/screenshot.png)

**CoreUI** es un entorno visual de alto rendimiento diseñado para terminales de control y estaciones de trabajo. Inspirado en interfaces HUD industriales, está optimizado específicamente para pantallas LCD con resoluciones de **1366x768** y **1080p**.

## 🎨 Paleta de Colores (LCD Optimized)

| Elemento | Color | Hex | Visual |
| :--- | :--- | :--- | :--- |
| **Acento Principal** | Cian LCD | `#00CCCC` | ![#00CCCC](https://via.placeholder.com/15/00CCCC?text=+) |
| **Fondo Base** | Negro Industrial | `#0e1210` | ![#0e1210](https://via.placeholder.com/15/0e1210?text=+) |
| **Fondo Alt** | Gris Carbón | `#151a17` | ![#151a17](https://via.placeholder.com/15/151a17?text=+) |
| **Texto/Primer Plano** | Blanco Glacial | `#e6f4ea` | ![#e6f4ea](https://via.placeholder.com/15/e6f4ea?text=+) |
| **Bordes/Divisores** | Verde Musgo | `#1f2a24` | ![#1f2a24](https://via.placeholder.com/15/1f2a24?text=+) |

## ✨ Características v1.1

- **Geometría Hard-Square:** Bordes de 0px en todos los widgets para máxima nitidez en paneles LCD.
- **GTK4 Engine Fix:** Migración completa de nodos para aplicaciones modernas (Libadwaita compatible).
- **Modo Compacto:** Reducción de paddings verticales, ideal para laptops de 1366x768.
- **Doble Panel Support:** CSS específico para paneles superiores e inferiores en Cinnamon.
- **Zero Ghosting:** Eliminación de transiciones de color para evitar el rastro en monitores de baja tasa de refresco.
- **Tipografía HUD:** Optimizado para el uso de `JetBrains Mono`.

## 🛠 Instalación

### Requisitos previos
Para la mejor experiencia en Cinnamon/GNOME, instala la fuente JetBrains Mono:
```bash
sudo apt install fonts-jetbrains-mono # En Debian/Ubuntu
