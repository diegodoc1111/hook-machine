---
name: hook-machine
description: Escribe hooks (ganchos) y títulos para reels, TikToks, shorts y anuncios con una librería de fórmulas probadas. Le das un tema y te devuelve 3 hooks, cada uno con una fórmula distinta, listos para el texto en pantalla y para decirlos a cámara. Úsala cuando alguien pida hooks, ganchos, títulos para un reel o un video, el texto en pantalla de un video, "los primeros 3 segundos", ideas para frenar el scroll, o variantes de gancho para probar en un anuncio.
---

# Hook Machine

El título de un reel o de un anuncio es lo primero que se lee: ahí la gente decide si se
queda o sigue de largo. Esta skill escribe esos títulos con fórmulas que ya funcionaron,
no a ojo.

## Antes de escribir

1. Lee completo `references/banco-de-ganchos.md`. Ahí están los principios del gancho,
   los 11 tipos y las plantillas virales A–N. No escribas ningún hook sin haberlo leído.
2. Si el usuario ya dio el tema, no preguntes nada: escribe con lo que hay y asume un
   público razonable para ese tema. Solo si no hay tema, pregunta en un único mensaje de
   qué trata el video y a quién le habla.
3. Voz del usuario: si pega textos suyos (captions, guiones, transcripciones), imita su
   forma de hablar: largo de las frases, palabras que usa, qué tan formal es. Si pasa links
   de sus redes y no puedes abrirlos, pídele que pegue el texto de 3 a 5 publicaciones.

## Qué entregar

Por defecto, 3 hooks, cada uno con una fórmula **distinta** del banco, en este formato:

```
3 opciones, con formato ganador:

01 · [nombre corto de la fórmula] → [título en pantalla]
     Dicho a cámara: "[lo que se dice en los primeros segundos]"
02 · ...
03 · ...
```

- **Título en pantalla:** máximo 10 palabras. Se tiene que entender sin sonido, porque la
  mayoría ve los videos sin audio.
- **Dicho a cámara:** una o dos frases para los primeros 2 a 3 segundos.
- Cierra con una sola línea: cuál de las 3 probarías primero y por qué.
- Si piden más hooks (10, 20...), dalos, pero rota las fórmulas: nunca la misma dos veces
  seguidas.

## Nombres cortos de las fórmulas

Usa estos nombres en la salida para que el usuario aprenda a reconocerlas:

| Nombre corto | En el banco |
|---|---|
| Promesa numerada | E) Lista / número |
| Kicker | A) Curiosidad: "Nadie te lo dijo…" |
| A vs B | Gancho 9) Dualidad y F) Comparación |
| Disrupción | Gancho 11) Disrupción + curiosidad + problema |
| Contraintuitivo | Gancho 5) y B) Afirmación audaz |
| El error | C) "La mayoría lo hace mal" |
| Pregunta de dolor | D) Pregunta de dolor y Gancho 2) |
| Eres tal persona | Gancho 1) Identificación |
| Antes y después | G) Resultado |
| Confesión | H) Detrás de cámaras |
| Urgencia | I) Urgencia temporal |
| FOMO | J) "Tu competencia ya…" |
| ¿Y si te dijera? | K) Revelación |
| Mira esto | L) Demostración |
| Deja de X | M) "Deja de [X]. Así es como [Y]" |
| Alerta | N) Enemigo común |
| Historia | Gancho 4) Escena concreta |

## Reglas

- **No inventes cifras, estudios ni resultados.** Si la fórmula pide un número o una prueba
  y el usuario no lo dio, déjalo entre corchetes, por ejemplo `[tu resultado real]`, y
  avísale que lo llene con un dato verdadero.
- Una idea por hook. Directo al punto: nada de "hola, hoy te voy a hablar de…".
- Escribe en el idioma y el registro del usuario (tú, vos o usted, según como escriba él).
- Evita las palabras que suenan a chatbot: "fascinante", "sumérgete", "descubre el secreto",
  "en el vertiginoso mundo de".

## Ejemplo

Usuario: `hooks para mi próximo video: agentes de IA que venden`

```
3 opciones, con formato ganador:

01 · Promesa numerada → 3 agentes que venden mientras duermes
     Dicho a cámara: "Estos 3 agentes de IA atienden y le venden a tus clientes mientras tú duermes."
02 · Kicker → Nadie te lo dijo: tu CRM ya puede contestar solo
     Dicho a cámara: "Nadie te lo dijo, pero tu CRM ya puede contestarle a tus leads solo. Mira cómo."
03 · A vs B → Vender antes de Claude / después de Claude
     Dicho a cámara: "Así vendía antes de Claude. Y así vendo ahora."

Probaría primero la 02: abre una pregunta en la cabeza y el que tiene un CRM se siente aludido.
```
