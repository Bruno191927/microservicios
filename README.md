# Microservicios
### Recomendaciones
* Tener docker instalado
* Tener nodejs instalado
-----------------------------
### Instalar Nestjs
```bash
npm i -g @nestjs/cli
```
### Instalacion de kafka (Se necesita docker)
* Clonar el siguiente repositorio
    ```bash
    git clone https://github.com/obsidiandynamics/kafdrop.git
    ```
* Entrar a la carpeta docker-compose\kafka-kafdrop y ejecutar
    ```bash
    docker-compose up
    ```
## Correr los proyectos
### Base de datos
* Entrar al proyecto cliente-microservice y ejecutar
```bash
    docker-compose up
```
 * Esto levantara la base de datos mongodb

### Instalacion de paquetes

* Ejecutar en cada proyecto
```
npm install
```

* Despues 
```bash
npm run start:dev
```


