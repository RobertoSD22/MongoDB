# Comando para entrar a la terminal de ese contenedor de docker

```sh
docker-compose exec <nombredelservicio> bash
```
ejemplo:
```sh
docker-compose exec mongodb bash
```

# Comando para conectarse con mongosh
```sh
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
```

# Comando para que una vez estando en mongosh muestre las BD´s existentes
```sh
show dbs
```

