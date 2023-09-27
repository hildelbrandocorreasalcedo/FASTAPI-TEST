# FASTAPI-TEST

documentacion completa de FastAPI in Containers - Docker
en https://fastapi.tiangolo.com/deployment/docker/

Al implementar aplicaciones FastAPI, un enfoque común es construir un Imagen de contenedor de Linux. Normalmente se hace usando Docker. Luego puede implementar esa imagen de contenedor de una de algunas maneras posibles.

![image](https://github.com/hildelbrandocorreasalcedo/FASTAPI-TEST/assets/63067085/b0d3371d-28ff-4cf9-8fbd-20252de372e4)

## Se debe crear el Container en docker con este comando: docker build -t fastapi-test .

![image](https://github.com/hildelbrandocorreasalcedo/FASTAPI-TEST/assets/63067085/bbbf7c0b-2430-4a72-8bdd-292350bb0569)

## Comando para ver los archivos: ls

![image](https://github.com/hildelbrandocorreasalcedo/FASTAPI-TEST/assets/63067085/860b5460-c536-478c-95fe-c380e9f1381a)

##Vemos la creacion de la imagen fastapi-test 

![image](https://github.com/hildelbrandocorreasalcedo/FASTAPI-TEST/assets/63067085/177821f6-22a0-4753-bfea-0ac7e140284d)

## Luego este comando: docker run -d --name fastapi-test -p 80:80 fastapi-test

para crear un contenedor llamado "fastapi-test" a partir de la imagen "fastapi-test", ejecutarlo en segundo plano, y mapear el puerto 80 del contenedor al puerto 80 del host. Esto es útil cuando deseas ejecutar una aplicación web (por ejemplo, una aplicación FastAPI) en un contenedor Docker y hacer que esté disponible en el puerto 80 de tu máquina host para que puedas acceder a ella a través de un navegador web u otras aplicaciones.

![image](https://github.com/hildelbrandocorreasalcedo/FASTAPI-TEST/assets/63067085/3d8fedb2-c761-476c-8aab-cac6468b7741)

## El siguiente comando para ver la imagen creada: Docker ps

![image](https://github.com/hildelbrandocorreasalcedo/FASTAPI-TEST/assets/63067085/62200d99-59b9-4c75-aed1-f1ad1560b43d)

## Entramos en la web en el puerto 80: http://localhost:80

![image](https://github.com/hildelbrandocorreasalcedo/FASTAPI-TEST/assets/63067085/484bd217-7512-48de-94ff-deb8f8210ece)

## Tambien podemos verificar la Api por el siguiente enlace: http://localhost:80/docs

![image](https://github.com/hildelbrandocorreasalcedo/FASTAPI-TEST/assets/63067085/dbea1df1-949c-4038-96e1-e11ee5bd20d4)
![image](https://github.com/hildelbrandocorreasalcedo/FASTAPI-TEST/assets/63067085/4fd86356-9c04-41cf-9eb1-2adc6bef732e)




