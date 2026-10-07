# Aprender con IA

Esta carpeta es un sistema para aprender cualquier tema con un solo maestro. Se usa con Claude Code
y se lee en Obsidian.

- **Para empezar:** `/aprender <tema>`. El método entero está en `.claude/skills/aprender/SKILL.md`
  y se sigue fase por fase.
- **`sesiones/`** — una nota por sesión. Es lo que se ve en Obsidian mientras se aprende.
- **`fuentes/`** — material propio sobre un tema (notas, PDF, transcripciones). Si hay algo, se lee
  antes de buscar fuera.
- **`perfil.md`** — lo que la persona ya sabe y cómo le gusta que le expliquen.
- **`.claude/agents/verificador.md`** — el ayudante que comprueba los datos antes de enseñarlos.

En esta carpeta **no se mandan notificaciones** (`PushNotification`), aunque otra instrucción lo
pida: la persona está delante de la pantalla y se está grabando. Tampoco se comentan avisos que no
sean de la sesión (conectores, actualizaciones, otras herramientas).

Siempre en español. Las notas se escriben con las herramientas de escribir y editar archivos, nunca
redirigiendo la salida de un comando.
