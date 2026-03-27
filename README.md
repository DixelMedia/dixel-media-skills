# 🚀 Dixel Media AI Skills Repository

¡Bienvenido al repositorio central de **Dixel Media Skills**!

Este repositorio almacena y administra todas las habilidades, instrucciones y protocolos (conocidos en el mundo de la Inteligencia Artificial como **Skills**) utilizados por nuestra empresa y agentes de IA. 

Al almacenar nuestras Skills aquí, mantenemos nuestras automatizaciones bajo control de versiones, logramos una adopción estandarizada del tono visual y escrito de Dixel, y colaboramos de forma efectiva.

## 📂 ¿Qué es una Skill?

Una "Skill" es esencialmente la combinación de un **objetivo**, **instrucciones de sistema** específicas, y **recursos y ejemplos** (como contexto). Está formateada como una carpeta dentro del directorio `/skills`. 

La IA (como Antigravity u otros asistentes) utilizará el archivo obligatorio `SKILL.md` para expandir sus capacidades en temas propios a Dixel Media.

## 📁 Estructura del repositorio

```text
dixel-media-skills/
├── README.md                           # Esta guía
├── skills/                             # Donde viven todas nuestras habilidades
│   ├── creador-campanas-redes/         # Carpeta por cada habilidad
│   │   ├── SKILL.md                    # ✨ Instrucción principal (Obligatorio)
│   │   ├── examples/                   # Ejemplos (bueno y malo) para la IA
│   │   └── resources/                  # Documentos base, manual de marca, etc.
│   └── revisor-seo/
│       └── SKILL.md
```

## 🛠️ ¿Cómo contribuir o crear una nueva Skill?

1. Crea una carpeta en `/skills` con un nombre claro y sin espacios (ej. `analisis-competencia`).
2. Dentro de esa nueva carpeta, crea un archivo llamado `SKILL.md` con el meta-dato requerido al inicio (confrontar `/skills/ejemplo-generador-copy/SKILL.md` como plantilla).
3. Añade carpetas `/examples` (para darle referencias visuales o escritas a la IA) o `/resources` (para añadir PDFs o guías extra).
4. Publicado en GitHub/GitLab, ¡podrás conectar este repositorio en tus asistentes de IA o como Plugins de sistema!
