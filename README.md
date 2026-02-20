# 🤖 The Robot Academy — IA & Data Science

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-181717?logo=github)](https://therobotacademy.github.io/)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](LICENSE)

Repositorio principal de publicaciones públicas sobre **Inteligencia Artificial** y **Data Science** por The Robot Academy.

🔗 **[Ver publicaciones → therobotacademy.github.io](https://therobotacademy.github.io/)**

---

## 📚 Publicaciones

| # | Título | Tipo | Nivel | Duración |
|---|--------|------|-------|----------|
| 1 | [Introducción a Google ADK con Python](codelabs/adk-intro.html) | Codelab | Intermedio | 45 min |

---

## 🗂 Estructura del repositorio

```
therobotacademy.github.io/
├── index.html          # Página principal con listado de publicaciones
├── codelabs/           # Codelabs interactivos
│   └── adk-intro.html  # Introducción a Google Agent Development Kit
└── README.md
```

---

## ➕ Añadir una nueva publicación

1. **Coloca el archivo HTML** en la carpeta correspondiente (`codelabs/`, `articles/`, etc.).
2. **Añade una tarjeta** en `index.html` dentro del div `#posts-grid`:

```html
<a class="card"
   href="codelabs/mi-nuevo-codelab.html"
   data-tags="python llm agentes"
   data-title="Mi Nuevo Codelab"
   style="--card-color-1:#1a73e8; --card-color-2:#0f9d58;">
  <div class="card-banner"></div>
  <div class="card-body">
    <span class="card-type">Codelab</span>
    <h2 class="card-title">Mi Nuevo Codelab</h2>
    <p class="card-summary">Descripción breve del contenido.</p>
    <div class="card-tags">
      <span class="tag blue">Agentes IA</span>
      <span class="tag">Python</span>
    </div>
    <div class="card-footer">
      <div class="card-meta">
        <span class="meta-item">30 min</span>
        <span class="meta-item">6 pasos</span>
      </div>
      <span class="card-level level-beginner">Principiante</span>
    </div>
  </div>
</a>
```

3. **Actualiza las estadísticas** en la sección hero de `index.html` si es necesario.
4. **Actualiza este README** con la nueva entrada en la tabla de publicaciones.

### Colores de banner disponibles

| Estilo | Color 1 | Color 2 |
|--------|---------|---------|
| Azul-Verde (defecto) | `#1a73e8` | `#0f9d58` |
| Azul-Morado | `#1a73e8` | `#7b2ff7` |
| Naranja-Rojo | `#f9ab00` | `#d93025` |
| Verde-Azul Claro | `#0f9d58` | `#00bcd4` |

### Niveles de dificultad

| Clase CSS | Etiqueta |
|-----------|----------|
| `level-beginner` | Principiante |
| `level-intermediate` | Intermedio |
| `level-advanced` | Avanzado |

### Filtros de chip disponibles

Los filtros activos en la barra superior son: `agentes`, `llm`, `python`, `gcp`. Para añadir un nuevo filtro:

1. Añade un `<button class="chip" data-filter="nuevo-tema">Nuevo Tema</button>` en `#filter-chips`.
2. Incluye `nuevo-tema` en el atributo `data-tags` de las tarjetas correspondientes.

---

## 📜 Licencia

Apache 2.0 — ver [LICENSE](LICENSE).

```
Copyright 2025 Bernardo Ronquillo Japón
```

---

## 👤 Autor

**Bernardo Ronquillo** — Experto en Data Science & IA

- 🐙 [GitHub](https://github.com/therobotacademy)
