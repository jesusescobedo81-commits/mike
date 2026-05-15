# IJAT · Índice de Justicia Ambiental Transfronteriza

> **Dashboard interactivo** · Tesis doctoral UABC 2026

[![Ver Dashboard](https://img.shields.io/badge/▶_Ver_Dashboard-1a5fa8?style=for-the-badge)](https://escobedo-ijat.github.io/ijat-dashboard/)
[![Tesis UABC](https://img.shields.io/badge/UABC-Facultad_de_Economía_y_RRII-0e9f6e?style=for-the-badge)](#)

---

## ¿Qué es el IJAT?

El **Índice de Justicia Ambiental Transfronteriza (IJAT)** es un instrumento compuesto que cuantifica y compara la justicia ambiental a ambos lados de la frontera Tijuana–San Diego en una escala de 0 a 1, donde 1 representa justicia ambiental óptima.

```
IJAT = (D1 · w₁) + (D2 · w₂) + (D3 · w₃)   donde  w₁ = w₂ = w₃ = 0.33
```

---

## Resultados principales

|  | 🇲🇽 Tijuana | 🇺🇸 San Diego |
|---|---|---|
| **IJAT** | **0.30** — Injusticia Ambiental | **0.80** — Alta Justicia Ambiental |
| D1 · Exposición a PM₂.₅ | 0.32 | 0.88 |
| D2 · Vulnerabilidad Social | 0.42 | 0.82 |
| D3 · Capacidad Institucional | 0.18 | 0.71 |
| PM₂.₅ promedio multianual | 24.0 µg/m³ | 8.8 µg/m³ |
| Presupuesto ambiental per cápita | $2.60 USD | $48.00 USD |

> La brecha de **0.50 puntos** no se explica por un factor único, sino por la convergencia de déficits en las tres dimensiones. La cuenca atmosférica es compartida; los riesgos se experimentan de forma radicalmente distinta a cada lado de la frontera.

---

## Contenido del dashboard

El archivo `IJAT_simple.html` es una aplicación web autocontenida (sin dependencias externas salvo fuentes y Chart.js vía CDN) con seis secciones navegables:

| # | Sección | Contenido |
|---|---|---|
| 01 | **Puntajes** | Resultado final IJAT con escala de interpretación |
| 02 | **Dimensiones** | Desagregación D1 / D2 / D3 con gráfica de radar |
| 03 | **PM₂.₅** | Serie histórica 2022–2025, crecimiento interanual |
| 04 | **Salud** | Muertes prematuras, mortalidad respiratoria, asma infantil |
| 05 | **Institucional** | Tabla comparativa de capacidades; presupuesto per cápita |
| 06 | **Metodología** | Fórmula IJAT, pasos de construcción, Índice Relativo (Iₛₜ) |

---

## Cómo usar

### Opción A — GitHub Pages (recomendado para compartir)

1. Haz fork de este repositorio
2. Ve a **Settings → Pages → Source: main / root**
3. Comparte la URL: `https://TU-USUARIO.github.io/ijat-dashboard/IJAT_simple.html`

### Opción B — Local

```bash
git clone https://github.com/TU-USUARIO/ijat-dashboard.git
cd ijat-dashboard
# Abre IJAT_simple.html en cualquier navegador moderno
open IJAT_simple.html
```

No requiere servidor ni instalación de dependencias.

---

## Fuentes de datos

| Base | Descripción |
|---|---|
| **SINAICA** | Sistema Nacional de Información de la Calidad del Aire |
| **EPA-AQS** | Air Quality System (U.S. EPA) |
| **OMS / IHME** | Carga global de enfermedad, mortalidad atribuible |
| **CDC-ATSDR** | Salud ambiental y respiratoria |
| **INECC / SEMARNAT** | Inventarios de emisiones, política ambiental México |
| **CalEPA / CARB** | Regulación ambiental California |

Período de análisis: **2022–2025**

---

## Cita académica

```
Escobedo De la Torre, J.M. (2026). Índice de Justicia Ambiental Transfronteriza
(IJAT): Una comparativa Tijuana–San Diego. Tesis doctoral. Universidad Autónoma
de Baja California, Facultad de Economía y Relaciones Internacionales.
```

---

## Licencia

Este trabajo se comparte con fines académicos y de divulgación. Para uso, adaptación o reproducción, por favor contacta al autor.

---

<div align="center">
<sub>Desarrollado por Escobedo De la Torre, J.M. · UABC 2026 · Tijuana, Baja California</sub>
</div>
