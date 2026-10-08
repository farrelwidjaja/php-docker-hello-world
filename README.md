# PHP Docker Hello World

A simple PHP Hello World application running inside Docker using Docker Compose and Apache.

## Project Structure

```text
php-docker-hello-world/
├── docker-compose.yml
└── src/
    └── index.php
```

## How to Run

1. Clone this repository:
   ```bash
   git clone <repo-url>
   cd php-docker-hello-world
   ```

2. Start the Docker container:
   ```bash
   docker compose up -d
   ```

3. Open your browser and navigate to:
   ```text
   http://localhost:8080
   ```

4. To stop the container:
   ```bash
   docker compose down
   ```
