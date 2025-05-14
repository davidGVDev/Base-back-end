# 🚀 NestJS Backend Skeleton

Un esqueleto base para proyectos backend con NestJS, TypeORM y PostgreSQL.

## ⭐ Características

- Estructura base de NestJS
- Configuración de TypeORM
- Conexión a PostgreSQL
- Docker Compose listo para usar
- Configuración de variables de entorno
- Estructura de módulos básica
- Manejo de errores centralizado
- Validación de datos con class-validator
- Documentación Swagger lista

## 🛠️ Tecnologías Principales

- NestJS
- TypeORM
- PostgreSQL
- Docker
- Class Validator
- Swagger

## 📋 Requisitos Previos

- Node.js (v14 o superior)
- npm o yarn
- Docker y Docker Compose
- PostgreSQL (opcional si usas Docker)

## 🚀 Instalación

```bash
$ npm install
```

## ⚙️ Configuración

1. Clona el repositorio:
```bash
$ git clone https://github.com/tu-usuario/nestjs-backend-skeleton.git
```

2. Crea un archivo `.env` en la raíz del proyecto:
```
DB_HOST=localhost
DB_PORT=5432
DB_NAME=tu_db_name
DB_USERNAME=postgres
DB_PASSWORD=tu_password
```

## 🏃‍♂️ Ejecución

```bash
# desarrollo
$ npm run start

# modo desarrollo con recarga automática
$ npm run start:dev

# modo producción
$ npm run start:prod
```

## 🐳 Docker

Inicia la base de datos con Docker:

```bash
$ docker-compose up -d
```

## 📁 Estructura del Proyecto

```
src/
├── common/         # Utilidades compartidas
├── config/         # Configuraciones
├── modules/        # Módulos de la aplicación
├── main.ts         # Punto de entrada
└── app.module.ts   # Módulo principal
```

## 📚 Documentación API

La documentación Swagger está disponible en:
```
http://localhost:3000/api/docs
```

## 🧪 Pruebas

```bash
# pruebas unitarias
$ npm run test

# pruebas e2e
$ npm run test:e2e

# cobertura
$ npm run test:cov
```

## 📦 Dependencias Principales

```json
{
  "@nestjs/common": "^10.0.0",
  "@nestjs/config": "^3.0.0",
  "@nestjs/typeorm": "^10.0.0",
  "@nestjs/swagger": "^7.0.0",
  "@nestjs/jwt": "^10.0.0",
  "class-validator": "^0.14.0",
  "typeorm": "^0.3.0",
  "pg": "^8.11.0"
}
```

## 📝 Scripts Disponibles

```json
{
  "start": "nest start",
  "start:dev": "nest start --watch",
  "start:debug": "nest start --debug --watch",
  "start:prod": "node dist/main",
  "build": "nest build",
  "test": "jest",
  "test:watch": "jest --watch",
  "test:e2e": "jest --config ./test/jest-e2e.json"
}
```

## 🤝 Contribuir

1. Haz un Fork del proyecto
2. Crea tu rama de características (`git checkout -b feature/AmazingFeature`)
3. Haz commit de tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Haz Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📄 Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo [LICENSE](LICENSE) para más detalles.

