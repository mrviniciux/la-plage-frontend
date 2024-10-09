# La Plage - Beach Club Website

![Screen Shot 2024-09-20 at 15 51 01](https://github.com/user-attachments/assets/cebdff8b-bdee-44c3-a587-dc73f012b011)

This is a fork from https://github.com/technext/gourmet

Stack:

HTML5
CSS3
JS

## Running with Docker and nginx

Common URL: http://localhost:8080/

- Make sure you've docker installed
- Open a terminal on `la-plage-frontend` folder
- Execute the following commands

docker build -t la-plage-frontend .
docker run -p 8080:80 la-plage-frontend
