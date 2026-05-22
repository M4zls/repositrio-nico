# Proyecto DevOps - Sistema de Despachos y Ventas

Sistema integral de gestión de despachos y ventas con arquitectura de microservicios.

## 🏗️ Estructura del Proyecto

### Backend
- **Despachos API** (Spring Boot): Gestión de despachos
- **Ventas API** (Spring Boot): Gestión de ventas

### Frontend
- **React + Vite**: Interfaz de usuario para despachos

### DevOps
- **Docker Compose**: Orquestación de servicios
- **GitHub Actions**: CI/CD automático

## 🚀 Cómo Comenzar

### Prerequisitos
- Docker y Docker Compose
- Java 11+
- Node.js 16+

### Desarrollo Local

```bash
# Clonar repositorio
git clone https://github.com/M4zls/repositrio-nico.git
cd repositrio-nico

# Iniciar servicios con Docker Compose
docker-compose up -d
x
# Frontend (desarrollo)
cd front_despacho
npm install
npm run dev
```

## 📝 Branching Strategy

- `main`: Rama principal (producción)
- `deploy`: Rama de deployment

## 📦 Servicios

| Servicio | Puerto | Tecnología |
|----------|--------|-----------|
| Despachos API | 8080 | Spring Boot |
| Ventas API | 8081 | Spring Boot |
| Frontend | 5173 | React + Vite |
| Base de Datos | 5432 | PostgreSQL |

---

**Proyecto creado y sincronizado correctamente con GitHub**
