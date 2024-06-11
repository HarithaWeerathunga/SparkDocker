# SparkDocker

SparkDocker is a Docker Compose setup to quickly get a Spark cluster running on your machine. This setup includes a Spark master and a Spark worker.

## Prerequisites

- Docker
- Docker Compose

## Setup

1. Clone this repository to your local machine:
    ```sh
    git clone https://github.com/yourusername/SparkDocker.git
    cd SparkDocker
    ```

2. Start the Spark cluster using Docker Compose:
    ```sh
    docker-compose up -d
    ```

3. Access the Spark master web UI at `http://localhost:8080`.

