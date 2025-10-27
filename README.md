# django_api

Django REST API Project được tạo tự động bởi **Dev Portal**.

## 📋 Thông tin Project

- **Project Name:** django_api
- **App Name:** api
- **Django Version:** 4.2.7
- **DRF Version:** 3.14.0

## 🚀 Models

- **User**: users/

## 📦 Installation

```bash
# Clone repository
git clone https://github.com/quanmbl4255142/django-test-82.git

# Install dependencies
pip install -r requirements.txt

# Run migrations
python manage.py makemigrations
python manage.py migrate

# Create superuser
python manage.py createsuperuser

# Run server
python manage.py runserver
```

## 🐳 Docker

```bash
# Build image
docker build -t django_api .

# Run container
docker run -p 8000:8000 django_api
```

## 🔗 API Endpoints

- GET/POST `/api/users/` - List/Create User
- GET/PUT/DELETE `/api/users/<id>/` - Detail/Update/Delete User
- GET `/api/health/` - Health check

## 📝 License

MIT License
