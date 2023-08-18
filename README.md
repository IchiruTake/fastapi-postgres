# FASTAPI-POSTGRESQL
Template for building FastAPI applications with PostgreSQL

# Features
 - FASTAPI
 - POSTGRESQL
 - DOCKER-COMPOSE
 - Authentification
 - MIGRATION WITH Alembic

## Here are the steps to follow in order to run the program: 
After cloning the repository, go to it. 
 1. DOCKER COMPOSE
    ```
    docker-compose up
    
    ```

 2. RUN FRIST MIGRATION
      ```
      docker-compose exec app alembic revision --autogenerate -m "first migration"
      docker-compose exex app alembic upgrade head
      ```
 3. Please turn on the LISTEN Docs app. `0.0.0.0:8081/docs`

 4. EXAMPLE
    ![IMAGE](./img/img.png)
