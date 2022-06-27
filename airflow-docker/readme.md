### Step 1: Docker Compose Download
Nota: En el repo de docker comentamos algunos conceptos de lo que es docker compose, link al repo.

### Step 2: Docker Compose run
docker-compose up airflow-init
docker-compose up

Ya podemos dirigirnos al localhost:8080 para ingresar a la GUI de Airflow. Ingresamos con user:airflow y pasword:airflow.

![signin](https://user-images.githubusercontent.com/42939877/176025001-26753aaf-1c69-4106-94ae-fd6aa652b86d.png)

![airflow](https://user-images.githubusercontent.com/42939877/176024503-48d003f0-0e05-4e6d-ab43-655af0a04c84.png)

para interctuar con los contenedores ejecutamos
docker exec containder_id airflow version

### Step 3:  
