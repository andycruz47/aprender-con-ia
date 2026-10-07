# Aprender con inteligencia artificial

Un sistema para aprender cualquier tema con Claude Code como maestro. Le dices qué quieres aprender, te pregunta qué sabes ya, comprueba los datos antes de enseñarte y te arma un plan por pasos con preguntas en cada uno. Todo queda escrito en notas que puedes leer en Obsidian.

## Lo que necesitas

- [Claude Code](https://claude.com/claude-code) instalado y con tu cuenta iniciada
- [Obsidian](https://obsidian.md) si quieres leer las notas mientras aprendes (opcional)

## Cómo empezar

1. Descarga el repositorio en ZIP (botón verde **Code**, luego **Download ZIP**) y descomprímelo, o clónalo

   ```
   git clone <url-de-este-repositorio>
   ```

2. Abre una terminal dentro de la carpeta y arranca Claude Code

   ```
   claude
   ```

   La primera vez te pregunta si confías en la carpeta. Di que sí, así se activan sus permisos.

3. Escribe el tema que quieres aprender

   ```
   /aprender cómo funciona el GPS
   ```

4. Si usas Obsidian, abre la carpeta como bóveda y mira `sesiones/`. Ahí va apareciendo tu nota.

## Qué hay dentro

| Archivo | Para qué |
|---|---|
| `perfil.md` | Lo que ya sabes y cómo te gusta que te expliquen. Si lo llenas, te hace menos preguntas al principio |
| `fuentes/` | Tu propio material sobre el tema (notas, PDF, transcripciones). Lo lee antes de buscar en internet |
| `sesiones/` | Una nota por cada sesión, con tu plan, tus respuestas y la prueba final |
| `.claude/skills/aprender/` | El método, fase por fase |
| `.claude/agents/verificador.md` | El ayudante que comprueba cada dato antes de enseñártelo |
