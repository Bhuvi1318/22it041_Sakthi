# Need the below mentioned details as the submission
## 1 Commit the code in the respective files
Step 1: i written all my code in my respective files

![image](https://github.com/user-attachments/assets/e312ace7-22d2-4fbc-a2dc-43813645e1a9)

## 2 Screenshots and commands that you used to build the docker image. Pls note the image name should be `Reg-Number-personal-api(Example: 1214214-personal-api)`
**commands :**
1) `docker build -t 22it041-personal-api .`
2) `docker run -p 5000:5000 22it041-personal-api`

**1)Name : **

![image](https://github.com/user-attachments/assets/3aa3e94d-042b-478b-a102-41a197fae492)

**2) Register :**
 
![image](https://github.com/user-attachments/assets/ef747075-2c50-4a52-aecd-0f6cf29ed0cb)

**3) department :**
 
![image](https://github.com/user-attachments/assets/529a777a-b23d-40ce-8022-f43837c9cc40)




## 3 Get your friend's docker image and create a compose.yml and add the screenshots and commands here. Pls ensure that you tested the app correctly
**my compose.yml code:**
version: '3.8'

services:
  flask-app:
    image: dharaneesh1318/personal-api:latest
    ports:
      - "5002:5000"
    container_name: personal-api-container
    restart: always
    
**commands :**
1) `docker pull dharaneesh1318/personal-api:latest`
2) `docker images`
3) `docker compose up`
4) `docker compose up -d`

1)**My friend image : Name **

![image](https://github.com/user-attachments/assets/d410b1ef-2097-4a9f-9232-7b9beb8a6e53)

2)** Reg Num:**

![image](https://github.com/user-attachments/assets/68424d06-22ca-4b3a-aa24-0d6fbc5ee4e2)

3) **Dept:**

![image](https://github.com/user-attachments/assets/f3b9fe99-1e00-4dd7-abde-2296f869bcf5)




## 4 Write Dockerfile for the python file `ml-model.py`. Create image and push to DockerHub `Reg-Number-ml-model(Example: 1214214-ml-model)`
commands :
1) `docker build -t bhuvi1318/22it041-ml-model:latest .`

2) `docker push bhuvi1318/22it041-ml-model:latest`

3) `docker pull bhuvi1318/22it041-ml-model:latest`

4) `docker pull bhuvi1318/22it041-ml-model:latest`

 ouput:
 
 ![image](https://github.com/user-attachments/assets/b0d6dd15-0599-421c-a7f0-c98b29b2154b)


## 4 Add your DockerHub username
## 5 Add your DockerHub Repo screenshot with 2 images
