# Instalación

## Requisitos

- Docker
- Cuenta de NeonDB
- Conexión a internet

## Pasos de instalación

1. Clonar el repositorio
2. Configurar las variables de entorno de `.env`
3. Leventar Docker con (con PHP + Apache) y ejecutar migrations + seeders

```bash
docker compose up -d
```

4. Acceder al proyecto desde el navegador (según puerto definido)

## Variables de entorno

- APP_ENV
- DB_HOST
- DB_URL
- DB_PORT
- DB_DATABASE
- DB_USER
- DB_PASSWORD
- JWT_SECERET
- JWT_ACCESS_EXPIRES
- JWT_REFRESH_EXPIRES
