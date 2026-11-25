# Skill de edición · Pedro Buerbaum

Edita reels en el estilo de Pedro Buerbaum: busto parlante minimal en plano único cuyo zoom nunca para, subtítulo fino en el centro,
palabra grande color arena detrás de la cabeza, golpes de zoom, un bloque de gráfico de línea sobre negro y video en tarjeta redondeada.
Entrenada con los 20 videos de este repositorio (495 escenas medidas).

## Instalar
1. Descarga `pedro-buerbaum-editing.zip` (botón **Download raw file**).
2. **Claude (claude.ai o app):** Ajustes → Capacidades → Skills → *Subir skill* → elige el zip.
   **Claude Code:** descomprime en `~/.claude/skills/pedro-buerbaum-editing/`.
   **ChatGPT / Gemini:** sube el zip al chat (o a un Proyecto/Gem) y escribe: «Lee EMPIEZA_AQUI.md y sigue SKILL.md».
3. Sube tu clip y escribe: «Edita este video con la skill pedro-buerbaum-editing».

## Qué trae
- `SKILL.md`, `REGLAS_GENERALES.md`, `docs/` (RULEBOOK, EDIT_LOGIC, FORMATOS, Katana, Edit Studio)
- `library/` — 495 ejemplos reales con hoja de fotogramas y ficha (qué, diseño, animación, por qué)
- `references/` — desglose toma por toma, lógica y energía de cada video
- `system/` — el motor: transcripción, corte, subtítulos, render (Remotion), sonido, panel A/B/C, recorte de persona (`matte.py`)
- `plugins/edit-studio/` — plugin de edición de Higgsfield

## Ejemplo (`ejemplo/`)
Borrador del clip de prueba, su plan (`beats.json`, `edit_plan.json`) y los prompts del material que faltaba.
