# Gamelearn AI Labs 2026 — Claude Code

Materiales de formación sobre **Claude Code** y programación agéntica para el equipo de Gamelearn.

**Site:** https://lordokami.github.io/gamelearn-ai-labs-2026-slides/

---

## Recursos

| Recurso | Descripción | Enlace |
|---------|-------------|--------|
| **Best Practices** | Presentación con las mejores prácticas oficiales de Claude Code | [Ver slides](https://lordokami.github.io/gamelearn-ai-labs-2026-slides/claude-code-best-practices.html) |
| **Tips & Tricks** | Consejos avanzados, atajos y flujos de trabajo | [Ver slides](https://lordokami.github.io/gamelearn-ai-labs-2026-slides/claude-code-tips.html) |
| **Cheat Sheet v3.1** | Referencia rápida exportable a PDF | [Ver cheat sheet](https://lordokami.github.io/gamelearn-ai-labs-2026-slides/claude-code-cheatsheet.html) |

---

## Contenidos del Cheat Sheet

- **Flujo de trabajo en 4 fases** — Explorar, Planificar, Implementar, Confirmar
- **La Regla de Oro** — Verificación autónoma para mejorar calidad 2x–3x
- **Entrevista Inversa** — Técnica para extraer requisitos antes de codificar
- **Prompting Avanzado** — Chain of Thought y Few-Shot prompting
- **`.claudesignore`** — Cómo ahorrar tokens excluyendo archivos irrelevantes
- **Enriqueciendo el contexto** — `@archivos`, imágenes, piping desde terminal
- **Antipatrones** — Errores comunes y cómo evitarlos
- **CLAUDE.md** — Configuración persistente por proyecto
- **Skills y MCP** — Integraciones con herramientas externas
- **Agents (Subagentes)** — Patrón investigador/ejecutor para tareas masivas
- **Hooks** — Git pre-commit y automatización post-run
- **Debugging Científico** — Flujo instrumentar → ejecutar → analizar → corregir
- **Comandos CLI** — `/cost`, `/clear`, `/compact`, `/model` y más

---

## Tecnologías

- [Reveal.js](https://revealjs.com/) — Framework de presentaciones (slides)
- [Tailwind CSS](https://tailwindcss.com/) — Estilos del cheat sheet
- [html2pdf.js](https://ekoopmans.github.io/html2pdf.js/) — Exportación a PDF
- [GitHub Pages](https://pages.github.com/) — Hosting estático con deploy automático en cada push a `main`

## Deploy

El site se despliega automáticamente vía GitHub Actions (`.github/workflows/pages.yml`) en cada push a `main`.
