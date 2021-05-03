# Docker compose de las dos aplicaciones Rails, las dos bases de datos Postgress y MongoDB, y RabbitMQ
Consta de las dos imagenes de las app que hemos creado para simular dos microservicios:
Aplicación Rails con MongoDB en docker-hub -> fjfdepedro/rails_mongo:3
Aplicación Rails con Postgres en docker-hub -> fjfdepedro/rails_postgres:6

Utilizamos las imagenes de las base de datos:
Mongo: mongo:4.2.8
Postgres: la última versión que haya

Y con la imagen Rabbitmq
Rabbitmq rabbitmq:3.8.2-management


