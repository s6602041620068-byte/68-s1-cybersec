# Cyber Security

## Information
- Thammasat  (BEW) 
- 6602041620068
- s6602041620068@email.ac.th

## Environment
```sh
cp env.simp .env
```

## Running a services
### Database
```sh
docker compose -f db.yaml up #monitoring
docker compose -f db.yaml up -d #backaround
```
### PG admin
```sh
docker compose -f admin.yaml up #monitoring
docker compose -f admin.yaml up -d #backaround
```

### Application
```sh
docker compose -f app.yaml up #monitoring
docker compose -f app.yaml up -d #backaround
```