# 🇨🇴 Tono Colombiano — Claude Skill

Un [Claude Skill](https://www.anthropic.com/news/skills) que hace que Claude
converse en el **tono conversacional colombiano**: cálido, cercano y
emocionalmente conectado, donde conversar no es solo intercambiar información
sino crear conexión.

*A [Claude Skill](https://www.anthropic.com/news/skills) that makes Claude
talk in a **Colombian conversational tone**: warm, close and emotionally
connected — where a conversation isn't just exchanging information, it's
creating connection.*

---

## 🇪🇸 Español

### ¿Qué hace?

Reproduce la "capa emocional" del habla en Colombia, capturando lo que de verdad
hace que una conversación "suene colombiana" —más allá del slang—:

- **Conversar es conectar, no solo informar.**
- **Leer el ambiente** y no dejar morir la charla.
- **Humor** que baja la tensión y crea cercanía.
- **Narrar, no solo contar**: convertir hasta lo cotidiano en una pequeña historia.
- **Escucha emocional activa** e integrar al que llega.
- Diminutivos, saludos afectuosos, muletillas y calibración regional
  (paisa, costeño, rolo, caleño).

### ⚠️ Importante: solo para uso informal

Este skill está pensado **únicamente para registros informales y personales**:
chats, mensajes relajados, contenido lúdico o creativo. **No está diseñado para
correos de trabajo, mensajes a clientes ni comunicación formal**, donde por
escrito el tono cálido e informal puede percibirse fuera de lugar. El propio
skill incluye esa restricción para que Claude no lo aplique en contextos
profesionales.

### Instalación

**Opción A — Archivo `.skill` (más fácil):**
1. Descarga [`tono-colombiano.skill`](./tono-colombiano.skill).
2. Súbelo en la sección de **Skills / Capabilities** de tu interfaz de Claude.

**Opción B — Manual / Claude Code:**
1. Copia la carpeta [`skills/tono-colombiano/`](./skills/tono-colombiano) a tu
   directorio de skills (por ejemplo `~/.claude/skills/` o el de tu proyecto).
2. Asegúrate de mantener la estructura `SKILL.md` + `references/`.

### Uso

En una conversación informal, pídeselo a Claude:

> "Hablá en tono colombiano"
> "Respondé como paisa"
> "Ponle sabor colombiano a esto"

### Estructura del repo

```
tono-colombiano-skill/
├── README.md
├── LICENSE
├── tono-colombiano.skill          # paquete listo para instalar
└── skills/
    └── tono-colombiano/
        ├── SKILL.md               # principios, mecánica y reglas
        └── references/
            └── lexico-y-ejemplos.md   # léxico, cortesía, ejemplos
```

---

## 🇬🇧 English

### What it does

It reproduces the "emotional layer" of how people talk in Colombia, capturing
what truly makes a conversation "sound Colombian" — beyond slang:

- **Conversation is connection, not just information.**
- **Reading the room** and never letting the conversation die.
- **Humor** that lowers tension and builds closeness.
- **Storytelling, not just reporting**: turning even everyday things into a
  little story.
- **Active emotional listening** and bringing newcomers in.
- Diminutives, warm greetings, fillers and regional calibration
  (paisa, costeño, rolo, caleño).

### ⚠️ Important: informal use only

This skill is intended **only for informal, personal registers**: chats, relaxed
messages, playful or creative content. It is **not meant for work emails, client
messages or formal communication**, where in writing the warm, informal tone can
come across as out of place. The skill itself includes that restriction so that
Claude won't apply it in professional contexts.

### Installation

**Option A — `.skill` file (easiest):**
1. Download [`tono-colombiano.skill`](./tono-colombiano.skill).
2. Upload it in the **Skills / Capabilities** section of your Claude interface.

**Option B — Manual / Claude Code:**
1. Copy the [`skills/tono-colombiano/`](./skills/tono-colombiano) folder into
   your skills directory (e.g. `~/.claude/skills/` or your project's).
2. Keep the `SKILL.md` + `references/` structure intact.

### Usage

In a casual conversation, just ask Claude:

> "Talk in a Colombian tone"
> "Reply like a paisa"
> "Give this some Colombian flavor"

---

## 🎬 Inspiración / Inspiration

Este skill se inspiró en el análisis de dos videos del mismo autor sobre la
forma de conversar de los colombianos. Las observaciones conceptuales provienen
de ahí; el léxico está anclado en el habla real de Colombia.

*This skill was inspired by two videos from the same creator analyzing the way
Colombians converse. The conceptual observations come from there; the lexicon is
grounded in real Colombian usage.*

- **La forma de conversar de los colombianos no es normal** — https://youtu.be/y0Ozkfln1Zk
- **El Colombiano Nunca Te Cuenta Algo "Normal"… y Esta es la Razón** — https://youtu.be/GtW4553sNyw

> Los créditos del análisis original corresponden a su autor. Este repositorio
> solo implementa esas ideas como un Claude Skill.

---

## 📄 Licencia / License

[MIT](./LICENSE) © 2026 Carlos Manuel Estévez Bretón

---

## 🤝 Contribuciones / Contributing

Sugerencias de léxico regional, ejemplos o mejoras son bienvenidas vía issues o
pull requests. *Suggestions for regional lexicon, examples or improvements are
welcome via issues or pull requests.*
