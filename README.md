# AgentAI - Agente IA Conversacional

Landing page para LAION: Agentes IA personalizados que responden 24/7, califican leads y agendan citas.

## Estructura del proyecto

```
AgentAI/
├── index.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   ├── js/
│   │   └── app.js
│   └── images/
│       ├── logo-laion.png
│       ├── agentes-ia-conectados.png
│       └── equipo-medico-digital.png
├── Dockerfile
├── nginx.conf
└── .dockerignore
```

## Despliegue en Easypanel (Hostinger)

1. Subir el repositorio a GitHub
2. En Easypanel, crear un nuevo servicio **App**
3. Seleccionar **GitHub** como fuente y conectar el repo
4. Easypanel detecta el `Dockerfile` automaticamente
5. Configurar el puerto a **80**
6. Desplegar

## Stack

- **Servidor:** nginx:alpine
- **Frontend:** HTML + Tailwind CSS (inline)
- **Contenedor:** Docker