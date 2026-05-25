# PSUSphere - Docker Setup

## Run with Docker (No installation needed except Docker)

1. Install Docker Desktop from https://docker.com
2. Clone this repo or copy the `for_client/docker-compose.yml`
3. Run:
   docker-compose up -d
4. Open http://localhost:8000
5. Create superuser:
   docker-compose exec web python manage.py createsuperuser