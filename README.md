# Rozek 🧠

AI assistant con memoria real, RAG semántico y sistema de agentes. Corre 100% en el navegador — sin servidor, sin instalación.

## Características

- **Memoria persistente** — semántica, episódica y por documentos
- **RAG local** — MiniLM-L6-v2 corre en el navegador con Transformers.js
- **Intent Router** — clasifica mensajes antes del pipeline para respuestas más rápidas
- **Multi-agent** — coordinación de agentes para tareas complejas
- **Eval pipeline** — evalúa calidad de cada respuesta automáticamente
- **Debate mode**, **Expression mode**, **Deep mode**

## Cómo usarlo

1. Abrí [la app](https://TU_USUARIO.github.io/rozek)
2. En el primer mensaje vas a ver el modal para agregar tu API key de Groq
3. Conseguí una key gratis en [console.groq.com](https://console.groq.com)
4. Pegála y listo — Rozek queda funcional

## Stack

- HTML + CSS + Vanilla JS (sin frameworks)
- [Groq API](https://groq.com) — LLM inference (llama-3.3-70b)
- [Transformers.js](https://huggingface.co/docs/transformers.js) — embeddings locales
- [JSONBin](https://jsonbin.io) — sync de memoria entre dispositivos (opcional)

## Desarrollo local

Cloná el repo y abrí `index.html` directo en el navegador. No necesitás servidor ni build step.

```bash
git clone https://github.com/TU_USUARIO/rozek
cd rozek
open index.html  # o doble click en el archivo
```

---

Creado por Nick
