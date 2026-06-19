# MentorIA ITZ 🎓
**Asistente de Inteligencia Artificial del Instituto Tecnológico de Zacatepec**
Creado por Mtro. José Alfredo Cortina Medina · DOCENC-IA LABS · ITZ-TecNM

---

## Archivos del proyecto

```
mentoria-itz/
├── index.html        ← Interfaz completa de Mentoría
├── api/
│   └── chat.js       ← Backend serverless (protege tu API key)
├── vercel.json       ← Configuración de despliegue
└── README.md         ← Este archivo
```

---

## Cómo publicar en 10 minutos

### Paso 1 — Obtén tu API key de Anthropic
1. Ve a https://console.anthropic.com
2. Crea tu cuenta
3. Ve a **API Keys** → **Create Key**
4. Copia la clave (empieza con `sk-ant-api03-...`)

### Paso 2 — Sube el proyecto a GitHub
1. Ve a https://github.com y crea una cuenta si no tienes
2. Clic en **"New repository"**
3. Nombre: `mentoria-itz`
4. Deja todo por defecto → clic en **"Create repository"**
5. En la siguiente pantalla, clic en **"uploading an existing file"**
6. Arrastra los 3 archivos: `index.html`, `vercel.json` y la carpeta `api/` con `chat.js`
7. Clic en **"Commit changes"**

### Paso 3 — Despliega en Vercel
1. Ve a https://vercel.com y entra con tu cuenta de GitHub
2. Clic en **"Add New Project"**
3. Selecciona tu repositorio `mentoria-itz`
4. Antes de desplegar, ve a **"Environment Variables"** y agrega:
   - **Name:** `ANTHROPIC_API_KEY`
   - **Value:** tu clave `sk-ant-api03-...`
5. Clic en **"Deploy"**
6. En 2 minutos tendrás tu URL: `mentoria-itz.vercel.app`

---

## Tu URL personalizada

Por defecto Vercel te da: `mentoria-itz.vercel.app`

Puedes cambiarla a algo como: `mentoria.itz.edu.mx` si el ITZ te proporciona un subdominio.

---

## Tecnología

- **Frontend:** HTML + CSS + JavaScript puro (sin frameworks)
- **Backend:** Serverless function en Node.js (Vercel)
- **IA:** Claude Sonnet (Anthropic) vía API
- **Hosting:** Vercel (gratuito)
- **Costo estimado:** ~$0.003 USD por conversación completa

---

## Créditos

Desarrollado con 💛 por el **Mtro. José Alfredo Cortina Medina**
Academia de Ciencias Básicas · ITZ-TecNM · Morelos, México
Proyecto **DOCENC-IA LABS** · *Explora. Aprende. Innova. Transforma.*
