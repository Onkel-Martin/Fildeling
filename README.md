# ITK-dev Fildeling

## Docker install

## Usage

### Requirement for all commands to work

### Templates

### Docker commands

Start containers:
```sh
docker-compose up -d
```

Stop containers: 
```sh
docker-compose stop
```

Stop and remove containers: 
```sh
docker-compose down
```

List containers in the project:
```sh
docker-compose ps
```

Restart container:
```sh
docker-compose restart <CONTAINER NAME>
```

Open Site:
```sh 
open "http://$(docker-compose port nginx 8080)"
```


```sh
docker compose up -d
docker compose exec phpfpm composer install
docker compose exec phpfpm bin/console doctrine:migrations:migrate --no-interaction
```

### Helper scripts
### Environment
#### Example .env file
## SSL certification support
## Completions
### Bash
### Zsh
## ITK Images
## More
## Previous versions
### NFS mounts removed