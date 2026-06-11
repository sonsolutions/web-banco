Para subir:

docker compose up -d

Para validar:

docker ps

A aplicação estará disponível em:

http://IP_DO_SERVIDOR:8080

E o PostgreSQL em:

IP_DO_SERVIDOR:5432
Com os dados: 
      POSTGRES_NAME: database
      POSTGRES_DATABASE: aplicacao
      POSTGRES_USER: admin
      POSTGRES_PASSWORD: senha123
