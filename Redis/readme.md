# Redis

Redis is a fast, open-source in-memory data store commonly used as a database, cache, and message broker.

## Running Redis with Docker

To run a Redis container using Docker, follow these steps:

1. Navigate to the directory containing your `docker-compose.yml` file.
2. Start the container with the following command:

	```sh
	docker-compose up
	```

3. To stop the container, use the keyboard shortcut `Ctrl + C`.

### Usage

To connect to Redis, use the following default settings:

- **Host:** `localhost`
- **Port:** `6379`
- **Volume:** `redis_data:/data`
- **Persistence:** `AOF enabled` (`--appendonly yes`) and snapshot every 60 seconds if at least 1 key changed (`--save 60 1`)

The first time you run this command, Docker will automatically download the necessary image. On subsequent runs, it will initialize the container without downloading the image again.
