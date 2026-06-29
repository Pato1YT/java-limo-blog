# Blog Java-Limo++

Blog oficial del Club de Programación Java-Limo++ del Instituto Tecnológico Superior de Huetamo (ITSH).

## Descripción

Plataforma web del club que incluye:
- Dashboard con estadísticas del club
- Perfiles de miembros
- Concursos y resultados (integración con OmegaUp)
- Recursos de estudio por nivel y tema
- Noticias y publicaciones
- Calendario de eventos
- Formulario de contacto

## Stack tecnológico

| Capa | Tecnología |
|------|-----------|
| Frontend | Next.js 16 + Tailwind CSS |
| Backend | Django 4.2 + Django REST Framework |
| Base de datos | PostgreSQL |
| Despliegue frontend | Vercel |
| Despliegue backend | Render |

## Estructura del proyecto
java-limo-blog/

├── backend/       # Django REST Framework

└── frontend/      # Next.js 16

## Instalación local

### Backend

```bash
cd backend
python -m venv venv
venv\Scripts\activate        # Windows
pip install -r requirements.txt
cp .env.example .env         # configura tus variables
python manage.py migrate
python manage.py runserver
```

### Frontend

```bash
cd frontend
npm install
cp .env.local.example .env.local   # configura tus variables
npm run dev
```

## Variables de entorno

### Backend (`backend/.env`)
SECRET_KEY=
DEBUG=
DB_NAME=
DB_USER=
DB_PASSWORD=
DB_HOST=
DB_PORT=

### Frontend (`frontend/.env.local`)
NEXT_PUBLIC_API_URL=

## Equipo
Club de Programación Java-Limo++ — ITSH
