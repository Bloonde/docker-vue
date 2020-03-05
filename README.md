# Docker Vue

Create .env

    $ cd docker-vue
    $ cp .env.example .env

Edit .env (Docker-vue)

    -PROJECT_NAME=project_name
    -IMAGE_NAME=vue // Not edited

Start:

    $ cd docker-vue
    $ ./start.sh
    
Run container and composer project

    $ docker exec -it project_name bash
    $ su docker
    
