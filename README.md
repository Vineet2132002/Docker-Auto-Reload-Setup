Template for dockerfile setup for live reloads.

### Run Developer Mode
Developer Mode - Live Changes like would when running normally. Use Dockerfile-dev & docker-compose-dev.yml
```
docker compose -f "docker-compose-dev.yml" up -d 
```
### For Development Mode
For shipping images or for devops mode use Dockerfile & docker-compose.yml
```
docker compose up
```
