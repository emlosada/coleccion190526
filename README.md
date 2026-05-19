# 🎮 RETRO VAULT — Colección Personal de Coleccionables

![Retro Gamer](https://img.shields.io/badge/Estética-16--BIT%20RETRO-00ff9d?style=for-the-badge)
![Items](https://img.shields.io/badge/Coleccionables-306-ff6b35?style=for-the-badge)
![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Ready-7c3aed?style=for-the-badge)

Una página web estilo **arcade retro 16-bit** para administrar y visualizar tu colección personal de videojuegos, consolas y libros. Impulsada por IA (Claude API) para generar fichas de lore de cada ítem.

---

## ✨ Features

- 🔍 **Buscador en tiempo real** por nombre, plataforma o editorial
- 📊 **Estadísticas y gráficos**: distribución por tipo, top plataformas, editoriales
- 🃏 **Cards interactivas** con links a Wikipedia, YouTube y PriceCharting
- 🤖 **Fichas de Lore con IA**: año de lanzamiento, curiosidades y resumen generados por Claude
- 💰 **PriceCharting** para juegos y consolas
- 🎨 **Estética CRT / 16-bit** con scanlines, fuentes pixel y efectos retro
- 📦 **306 ítems**: 218 juegos, 24 consolas, 18 libros y más

---

## 🚀 Deploy en GitHub Pages

1. Hacé un fork o subí este repositorio a GitHub
2. Andá a **Settings → Pages**
3. En *Source*, seleccioná `main` branch y carpeta `/ (root)`
4. ¡Listo! Tu colección estará en `https://tu-usuario.github.io/nombre-repo`

> **Nota:** Las fichas de lore usan la API de Claude (Anthropic). En GitHub Pages funcionan porque la API key se gestiona del lado del servidor de Anthropic via CORS público de claude.ai. Si deployás en otro hosting, puede requerir un backend proxy.

---

## 📁 Estructura

```
/
└── index.html      # Todo en un solo archivo, sin dependencias externas
└── README.md       # Este archivo
```

---

## 🛠 Tecnologías

- **HTML/CSS/JS** puro — sin frameworks, sin build tools
- **Press Start 2P** + **VT323** (Google Fonts) — tipografía pixel art
- **Claude API** (Anthropic) — generación de fichas de lore
- **GitHub Pages** compatible — un solo archivo estático

---

## 📷 Secciones

| Sección | Descripción |
|---|---|
| Header | Logo animado con efecto glitch |
| Stats Bar | Totales y porcentajes por categoría |
| Charts | Donut chart + barras de plataformas y editoriales |
| Controles | Buscador + filtros por tipo + selector de plataforma |
| Cards | Grid de ítems con links y botón de lore |
| Modal | Ficha detallada con lore generado por IA |

---

*INSERT COIN TO CONTINUE* 🪙
