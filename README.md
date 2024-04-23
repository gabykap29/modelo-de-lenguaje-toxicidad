# Plataforma de Cursos con Inteligencia Artificial

Este proyecto consiste en una plataforma de cursos en línea impulsada por inteligencia artificial para recomendación de contenido personalizado.

## Características principales

- Recomendación de cursos personalizados mediante inteligencia artificial.
- Catálogo de cursos con búsqueda y filtros.
- Perfiles de usuario con historial de cursos y preferencias.

## Tecnologías utilizadas

- TypeScript
- Node.js
- Express
- React
- FastAPI (para el servidor de IA en Python)
- GEMINI (modelo de inteligencia artificial)

## Instalación

### Backend (TS, Node, Express)

1. Clona el repositorio: `https://github.com/gabykap29/modelo-de-lenguaje-toxicidad.git`
2. Navega al directorio del backend: `cd server`
3. Instala las dependencias: `npm install`
4. Inicia el servidor: `npm run dev`

### Servidor de IA (Python, FastAPI)

1. Instala Python si no lo tienes instalado en tu sistema.
2. Navega al directorio del servidor de IA: `cd server AI`
3. Instala un entorno virtual: `pip install virtualenv`
4. Inicia el entorno virtual: `virtualenv env`
5. Instala las dependencias: `pip install -r requirement.txt`
6. Dentro de la carpeta crea un archivo llamado "clave.py" y declara la variable "clave" con tu API de Gemini.
7. Inicia el servidor con uvicorn: `uvicorn main:app --reload`

