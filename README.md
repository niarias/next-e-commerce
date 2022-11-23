# Next.js e-commerce
Para correr localmente, se necesita la base de datos.
```
docker-compose up -d
```


## Configurar las variables de entorno
Renombrar el archivo __.env.template__ a __.env__
* MongoDB URL Local:
```
MONGO_URL=mongodb://uri
```

* Reconstruir los módulos de node y levantar Next
```
yarn install
yarn dev
```


## Llenar la base de datos con información de pruebas

Llamara:
```
http://localhost:3000/api/seed
```

## Acerca del proyecto 
Este proyecto contiene todas las funcionalidades necesarias de un e-commerce.
Incluye codigo Backend y codigo Frontend.Ademas este proyecto incluye la funcionalidad de poder pagar con Paypall.
