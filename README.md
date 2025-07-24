# Hello World! - FastAPI & Docker

>This project it is to be able to understand at a very basic level how containers work with Docker. To do this, I have made an example API and then put it in a container and program it in the Dockerfile

## Requirements
- Docker Installed

## 🧠 What i Learned?
- How Docker works
- Add an app to a container
- Create an image


## Installation & Setup
1. Clone the repository (Use SSH link, make the public key)
    ```
    git clone git@github.com:CodriXAI/api-docker.git
    cd api-docker
    ```
2. Using Docker, build and then run the container
    ```
    docker build -t api-docker .
    docker run -p 8000:8000 api-docker
    ```
3. Test
    ```
    curl http://localhost:8000
    ```

## License
This project is licensed under the MIT License. Feel free to use it as a base for your own ideas.

## Autor
Built by @Cristian "CodriX" Colares - AI beginner 🇦🇷
