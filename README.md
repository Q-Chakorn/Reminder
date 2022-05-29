# Reminder
Introduction to Containers : https://container.training/intro-selfpaced.yml.html#1

 
 Docker Command
 
- docker build <สร้าง contrainer>
- docker run <run container>
- docker run -it -d <image>:tag
- docker exec -it <container-name , container-id> bash sh

- docker images <ดู image>
- docker rmi <image_id> <ลบ image>
- docker start , stop <contrainer_id> <เปิด ปิด contrainer>
- docker rm <contrainer_id> <ลบ contrainer>
- docker ps <ดู process>

- docker network create <name> 
- docker network ls
- docker network inspect <name> <ดูภายใน network>

- docker-compose up -d <start container จากไฟล์>
- docker-compose down <down container>
- docker-compose down --rmi all <down container และ ลบ all image>

--env file
- COMPOSE_PROJECT_NAME=<name> = ไม่ต่องใส่ container name ใน docker-compose.yaml 