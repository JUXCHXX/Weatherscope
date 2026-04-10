<div align="center">

# 🌐 WeatherScope

### Dashboard del clima en tiempo real — elegante, rápido y sin dependencias

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-weatherscope-63b3ed?style=for-the-badge)](https://TU_USUARIO.github.io/weatherscope)
[![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Open-Meteo](https://img.shields.io/badge/API-Open--Meteo-68d391?style=for-the-badge)](https://open-meteo.com)

<br/>

![WeatherScope Preview](https://images.unsplash.com/photo-1504608524841-42584120d693?w=900&q=80&auto=format&fit=crop)

> Un dashboard del clima construido con HTML, CSS y JavaScript vanilla.  
> Sin frameworks, sin API key, datos reales en tiempo real.

<br/>

[🚀 Ver Demo en Vivo](https://TU_USUARIO.github.io/weatherscope) · [🐛 Reportar Bug](https://github.com/TU_USUARIO/weatherscope/issues) · [💡 Solicitar Feature](https://github.com/TU_USUARIO/weatherscope/issues)

</div>

---

## ✨ Características

| Feature | Descripción |
|---|---|
| 🔍 **Búsqueda global** | Busca cualquier ciudad del mundo por nombre |
| 📍 **Geolocalización** | Detecta tu ubicación automáticamente |
| 🌡️ **Clima en tiempo real** | Temperatura, sensación térmica, humedad, viento y más |
| 📊 **Gráfica de pronóstico** | Visualización de temperaturas máximas y mínimas a 5 días |
| 📅 **Forecast 5 días** | Cards con ícono, máx y mín por día |
| 🔄 **°C / °F** | Toggle instantáneo entre unidades |
| 🕓 **Historial** | Últimas 5 ciudades buscadas (guardado en localStorage) |
| 🎨 **Fondo dinámico** | Cambia según la condición del clima |
| ⚡ **Sin dependencias** | Solo HTML + CSS + JS vanilla |

---

## 🖥️ Vista previa

<div align="center">

### Pantalla principal
![Dashboard principal](https://images.unsplash.com/photo-1592210454359-9043f067919b?w=800&q=80&auto=format&fit=crop)

### Pronóstico a 5 días
![Pronóstico](https://images.unsplash.com/photo-1530908295418-a12e326966ba?w=800&q=80&auto=format&fit=crop)

</div>

---

## 🛠️ Tecnologías

```
weatherscope/
├── index.html          ← Todo el proyecto en un solo archivo
│
├── Diseño
│   ├── CSS Variables   — Sistema de colores y tipografía
│   ├── Syne (Google Fonts) — Tipografía display
│   └── DM Mono         — Tipografía monoespaciada
│
├── APIs (gratuitas, sin API key)
│   ├── Open-Meteo      — Datos del clima en tiempo real
│   ├── Open-Meteo Geocoding — Búsqueda de ciudades
│   └── Nominatim       — Geocoding inverso (geolocalización)
│
└── Librerías
    └── Chart.js (CDN)  — Gráfica de pronóstico
```

---

## 🚀 Uso local

```bash
# 1. Clona el repositorio
git clone https://github.com/TU_USUARIO/weatherscope.git

# 2. Entra al directorio
cd weatherscope

# 3. Abre el archivo en tu navegador
open index.html
# o simplemente haz doble clic en index.html
```

> ✅ **No requiere servidor, npm install, ni configuración.** Abre y listo.

---

## 🌍 APIs utilizadas

Este proyecto usa APIs **100% gratuitas** sin necesidad de API key ni registro:

| API | Uso | Docs |
|---|---|---|
| [Open-Meteo](https://open-meteo.com) | Datos del clima y pronóstico | [Documentación](https://open-meteo.com/en/docs) |
| [Open-Meteo Geocoding](https://open-meteo.com/en/docs/geocoding-api) | Convertir nombre → coordenadas | [Documentación](https://open-meteo.com/en/docs/geocoding-api) |
| [Nominatim](https://nominatim.openstreetmap.org) | Geocoding inverso para geolocalización | [Documentación](https://nominatim.org/release-docs/latest/) |

---

## 📦 Deploy en GitHub Pages

1. Sube el archivo como `index.html` en la raíz del repositorio
2. Ve a **Settings → Pages**
3. En *Source* selecciona `Deploy from a branch`
4. Rama: `main`, carpeta: `/ (root)`
5. Clic en **Save**
6. En unos minutos tu app estará en:  
   `https://TU_USUARIO.github.io/weatherscope`

---

## 🎨 Diseño

El dashboard usa una paleta **dark tech** con acentos en azul hielo:

| Token | Color | Uso |
|---|---|---|
| `--bg` | `#080c14` | Fondo principal |
| `--surface` | `#0d1520` | Tarjetas |
| `--accent` | `#63b3ed` | Temperatura, botones, focus |
| `--accent2` | `#f6ad55` | Temperatura máxima |
| `--muted` | `#64748b` | Texto secundario |

Tipografía: **Syne** (display / títulos) + **DM Mono** (datos / monospace)

---

## 📄 Licencia

Distribuido bajo la licencia MIT. Consulta `LICENSE` para más información.

---

<div align="center">

Hecho con ❤️ y JavaScript vanilla

⭐ Si te gustó el proyecto, ¡dale una estrella!

</div>