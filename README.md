Se deben crear los contenedores de Docker en los puertos 4000 (app1) y 4001 (app2), con el comando docker-compose up --build en la terminal de la carpeta del repositorio.

Prueba de la conexión de la APP 1 con http://localhost:4000/tz?zone=America/New_York 

![image](https://github.com/user-attachments/assets/e4a98999-b311-4683-ae39-67e20ca42eb6)


Prueba de la conexión de la APP 2 con el enlace http://localhost:4001/checker?url=app1&zone=America/New_York 

![image](https://github.com/user-attachments/assets/0592d53d-a702-4b10-ac48-f0a2e1f3f1ef)


Prueba de la conexión de la APP 2 con el enlace http://localhost:4001/checker?url=app1&zone=America/Washington 

![image](https://github.com/user-attachments/assets/3aa01681-fd78-4bde-bd72-c9316a54d019)

