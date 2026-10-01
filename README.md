# Hook Machine — skill de Claude

Le das un tema y te devuelve **3 hooks listos para tu próximo reel o anuncio**, cada uno con
una fórmula distinta: el título que va en pantalla y lo que dices a cámara en los primeros
segundos.

El título es la parte más importante del hook: es lo primero que se lee y ahí la gente
decide si se queda o sigue de largo. Esta skill lo escribe con fórmulas que ya funcionaron,
no a ojo.

Hecha por [Diego Osorio](https://instagram.com/soydiegoosorio).

![fórmulas](https://img.shields.io/badge/fórmulas-25+-d9774f) ![Licencia](https://img.shields.io/badge/licencia-MIT-2d6a5c)

## Instalar en Claude (web o app de escritorio)

1. Descarga [**hook-machine.zip**](https://github.com/diegodoc1111/hook-machine/releases/latest/download/hook-machine.zip). No lo descomprimas.
2. Entra a [claude.ai/customize/skills](https://claude.ai/customize/skills).
3. Toca **+**, luego **Create skill** y luego **Upload a skill**. Sube el ZIP.
4. Activa la skill.

Funciona en cualquier plan de Claude, incluso el gratis. Si no te aparece la opción de
subir skills, activa primero la ejecución de código en la configuración de Claude.

## Instalar en Claude Code

Copia y pega esto en Claude Code:

```
Instala esta skill de Claude Code: clónala desde https://github.com/diegodoc1111/hook-machine dentro de ~/.claude/skills/
```

## Cómo se usa

Abre un chat nuevo y escribe:

```
hooks para mi próximo video: agentes de IA que venden
```

Te devuelve algo así:

```
3 opciones, con formato ganador:

01 · Promesa numerada → 3 agentes que venden mientras duermes
02 · Kicker → Nadie te lo dijo: tu CRM ya puede contestar solo
03 · A vs B → Vender antes de Claude / después de Claude
```

Cada opción trae también la versión para decir a cámara y, al final, cuál probaría
primero y por qué.

**Para que escriba con tu voz:** pégale el texto de 3 a 5 de tus publicaciones (captions,
guiones o transcripciones) y pídele los hooks. Imita tu forma de hablar.

## Qué trae adentro

`references/banco-de-ganchos.md` es la librería completa:

- **Los principios del gancho:** las 3 capas (visual, texto y lo que dices) y por qué el
  texto en pantalla tiene que funcionar sin sonido.
- **Los 11 tipos de gancho**, con fórmula y ejemplos: identificación, miedo u objeción,
  deseo, historia, contraintuitivo, ultra segmentado, personificado, venta directa,
  dualidad, pruebas, y disrupción + curiosidad + problema.
- **14 plantillas virales para rellenar (A–N):** curiosidad, afirmación audaz, el error,
  pregunta de dolor, lista, comparación, antes y después, confesión, urgencia, FOMO,
  "¿y si te dijera?", demostración, "deja de X" y alerta.
- **Ejemplos reales** con su tipo, para captar el tono.

La skill no inventa cifras ni resultados: si una fórmula pide un dato y no se lo diste,
te lo deja entre corchetes para que pongas el tuyo.

## Actualizaciones

Voy mejorando el banco con los anuncios y contenidos que pruebo y que funcionan en mis
clientes. Para tener la última versión:

- **Claude web o app:** descarga otra vez el ZIP y vuelve a subirlo.
- **Claude Code:** `git -C ~/.claude/skills/hook-machine pull`

## Licencia

MIT. Úsala, modifícala y compártela.
