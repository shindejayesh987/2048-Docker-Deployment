# 2048 Game - Dockerized Version

This is a Dockerized version of the classic 2048 game, originally created by [Gabriele Cirulli](https://github.com/gabrielecirulli/2048). This repository allows you to run the 2048 game in a Docker container for easy setup and deployment.

## Local Development

### Prerequisites

- [Docker](https://www.docker.com/)
- [Git](https://git-scm.com/) (for development)

### Running Locally

To run the 2048 game locally using Docker, follow these steps:

1. Pull the Docker image:
    ```sh
    docker pull jdshinde/2048-docker
    ```

2. Run the Docker container:
    ```sh
    docker run --rm -p 80:80 2048
    ```

3. Visit the game in your browser at: [http://localhost:80](http://localhost:80)

### Development

If you want to develop or modify the game, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/shindejayesh987/2048-Docker-Deployment
    ```

2. Navigate to the project directory:
    ```sh
    cd 2048-docker
    ```

3. Build the Docker image:
    ```sh
    docker build -t 2048 .
    ```

4. Run the Docker container:
    ```sh
    docker run --rm -p 80:80 2048
    ```

5. Visit the game in your browser at: [http://localhost:80](http://localhost:80)

## Acknowledgments

- [Gabriele Cirulli](https://github.com/gabrielecirulli) for creating the original 2048 game.

## Contact

For any questions or inquiries, please reach out to the maintainer at [jay98shinde@gmail.com](mailto:jay98shinde@gmail.com).
