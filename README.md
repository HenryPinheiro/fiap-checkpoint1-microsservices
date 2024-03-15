# fiap-checkpoint1-microsservices

## Para poder executar aplicação a partir da imagem no Docker Hub com profile "dev"
```
  docker pull henrypin/fiap-checkpoint1:latest
  docker run -p 8080:8080 -e "PROFILE=dev" henrypin/fiap-checkpoint1
```

## Para poder executar aplicação a partir da imagem no Docker Hub com profile "stg"

```
  docker pull henrypin/fiap-checkpoint1:latest
  docker run -p 8080:8080 -e "PROFILE=stg" henrypin/fiap-checkpoint1
```

## Para poder executar aplicação a partir da imagem no Docker Hub com profile "prd"

```
  docker pull henrypin/fiap-checkpoint1:latest
  docker run -p 8080:8080 -e "PROFILE=prd" henrypin/fiap-checkpoint1
```
