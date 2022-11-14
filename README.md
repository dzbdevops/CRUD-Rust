# CRUD-Rust
Containerized application in Rust language. The frontend and backend were not written by me. I created the containerization and exposing it to the "network" using NGNIX.
### My files:
```
- MAKE files
- docker-compose
- Dockerfiles
- ngnix.conf
- .env
```

## How to use CRUD-Rust?
1. Build with `make` frontend(api_to_autoamte_frontend) as well as backend(api_to_automate).
2. Set up in infrastructure folder by using `docker compose up`.

### Frontend and backend address:
```
http://rustapp_backend:8000/
http://rustapp_front:80/
```

### Endpoints:
```
POST: /doc
GET: /doc/<path>
GET(ALL): /doc
DELETE: /doc/<path>
PUT: /doc/<path>
GET: /health
```
