# goit-pythonweb-hw-10

Перед стартом проекту:

### Створіть файл `.env` в корені проекту:

```
DATABASE_URL=postgresql+asyncpg://admin:admin@db:5432/contacts
JWT_SECRET=your_jwt_secret
JWT_ALGORITHM=HS256
JWT_EXPIRATION_TIME=3600
CORS_ORIGINS=http://localhost,http://127.0.0.1:8000

MAIL_USERNAME=your_email@example.com
MAIL_PASSWORD=your_email_password
MAIL_FROM=your_email@example.com
MAIL_PORT=587
MAIL_SERVER=smtp.example.com
MAIL_FROM_NAME=FastAPI Contacts

CLOUDINARY_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### Запуск проекту

```
docker-compose up --build
```

### API Документація
- Swagger UI: http://localhost:8000/docs
- ReDoc UI: http://localhost:8000/redoc
