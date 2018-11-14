# levanta docker con el archivo docker-compose.yml
docker-compose up

# Obliga que al levandar cree la imagen de nuevo, util cuando se hace algun cambio.
docker-compose up --build

# Levanta y lo deja procesando en background.
docker-compose up -d

# Baja todos los contenedores.
docker-compose down