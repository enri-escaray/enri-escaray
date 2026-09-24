# Hola, soy Enrique 👋

### Desarrollador de software · Backend, datos e IA aplicada

[![LinkedIn](https://img.shields.io/badge/LinkedIn-enrique--escaray-0A66C2)](https://www.linkedin.com/in/enrique-escaray/)

Construyo software para problemas concretos: una plataforma minera que sigue funcionando sin conexión,
un agente legal con RAG, un SaaS para gimnasios. Trabajo sobre todo con **Python** y **TypeScript**,
bases de datos, pipelines de datos e IA aplicada, y cuido que lo que construyo sea confiable:
tests, CI, seguridad y decisiones de arquitectura documentadas.

🔭 Ahora mismo: ingeniería de datos ([market-data-pipeline](https://github.com/enri-escaray/market-data-pipeline))
y módulos de Odoo ([Obrador](https://github.com/enri-escaray/obrador)).

---

## Proyectos destacados

### ⛏️ [Mineral360](https://github.com/enri-escaray/minera-platform) — plataforma para operaciones mineras

Microservicios que corren dentro del sitio minero y **siguen operando aunque se caiga el enlace con el exterior**:
eventos idempotentes, colas *store-and-forward* y sincronización con la nube al reconectar. Cubre trazabilidad
del mineral, despacho de flota y mantenimiento predictivo, con seguridad por zonas (IEC 62443) y CI en GitHub Actions.

`Python` `FastAPI` `Kafka` `MQTT` `PostgreSQL` `TimescaleDB` `Docker` `K3s`

### 📹 [Vigía](https://github.com/enri-escaray/vigia) — videovigilancia inteligente

Analiza en tiempo real webcams, cámaras IP (RTSP) o transmisiones HLS, detecta comportamientos sospechosos
según la modalidad activa (en casa, nocturno, comercio abierto…) y dispara alertas con captura, clip y
notificaciones. Todo corre en local y sin reconocimiento facial.

`Python` `YOLO` `OpenCV` `FastAPI`

### ⚖️ [LexAR](https://github.com/enri-escaray/legal-rag-agent) — agente legal con RAG · [demo](https://legal-rag-agent-nzst.vercel.app)

Responde consultas de derecho civil y comercial argentino citando artículos reales del Código Civil y Comercial,
analiza expedientes en PDF y redacta borradores de contratos y cartas documento.

`Next.js` `Supabase` `pgvector` `Gemini` `Hugging Face`

### 🏋️ [CuotaFit](https://github.com/enri-escaray/CuotaFit) — SaaS para gimnasios · [app](https://cuotafit.vercel.app)

Socios, cobros y morosidad, planes por tiempo o por pases y un check-in por PIN tipo kiosco que funciona
sin internet (PWA). MVP en producción, multi-gimnasio y con los datos de cada gimnasio aislados con Row Level Security.

`Next.js` `React` `TypeScript` `Supabase` `Tailwind CSS`

---

## Más proyectos

| Proyecto | Qué es | Stack |
|---|---|---|
| [Obrador](https://github.com/enri-escaray/obrador) | Módulo de Odoo para gestión de obras: partes diarios, materiales, equipos y API REST | Python · Odoo · PostgreSQL |
| [Rendimiento Real](https://github.com/enri-escaray/rendimiento-real) · [demo](https://rendimiento-real.vercel.app) | Cuánto vale de verdad un ahorro en pesos después de la inflación, frente al plazo fijo | Next.js · TypeScript · Recharts |
| [market-data-pipeline](https://github.com/enri-escaray/market-data-pipeline) | Pipeline ELT: API de Binance → PostgreSQL → modelo estrella *(en construcción)* | Python · PostgreSQL · SQL |
| [Bóveda de Prompts API](https://github.com/enri-escaray/prompt-vault-api) · [docs](https://mi-boveda-api.onrender.com/api-docs/) | API REST para guardar y organizar prompts de IA, con JWT y Swagger | Node.js · Express · MongoDB |
| [Core IA](https://github.com/enri-escaray/core_ia) · [sitio](https://core-ia.vercel.app) | Landing page con animaciones y fondo tipo red neuronal | Next.js · Tailwind · Framer Motion |

---

## Tecnologías

| Área | Tecnologías |
|---|---|
| **Lenguajes** | ![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![SQL](https://img.shields.io/badge/SQL-4479A1) |
| **Backend y datos** | ![FastAPI](https://img.shields.io/badge/FastAPI-009688?logo=fastapi&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?logo=express&logoColor=white) ![Odoo](https://img.shields.io/badge/Odoo-714B67?logo=odoo&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?logo=postgresql&logoColor=white) ![TimescaleDB](https://img.shields.io/badge/TimescaleDB-FDB515?logo=timescale&logoColor=black) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?logo=mongodb&logoColor=white) ![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=white) ![Kafka](https://img.shields.io/badge/Kafka-231F20?logo=apachekafka&logoColor=white) ![MQTT](https://img.shields.io/badge/MQTT-660066?logo=mqtt&logoColor=white) |
| **Frontend** | ![Next.js](https://img.shields.io/badge/Next.js-000000?logo=nextdotjs&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB) ![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?logo=tailwindcss&logoColor=white) |
| **IA** | ![YOLO](https://img.shields.io/badge/YOLO-111F68?logo=ultralytics&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?logo=opencv&logoColor=white) ![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?logo=huggingface&logoColor=black) ![Gemini](https://img.shields.io/badge/Gemini-8E75B2?logo=googlegemini&logoColor=white) ![pgvector](https://img.shields.io/badge/pgvector-336791?logo=postgresql&logoColor=white) |
| **Infraestructura** | ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![K3s](https://img.shields.io/badge/K3s-FFC61C?logo=k3s&logoColor=black) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white) ![Vercel](https://img.shields.io/badge/Vercel-000000?logo=vercel&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?logo=render&logoColor=black) |
