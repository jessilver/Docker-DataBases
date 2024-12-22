# PostgreSQL

PostgreSQL is a powerful, open-source object-relational database system known for its reliability, feature robustness, and performance. It supports both SQL (relational) and JSON (non-relational) querying.

## Running PostgreSQL with Docker

To run a PostgreSQL container using Docker, follow these steps:

1. Navigate to the directory containing your `docker-compose.yml` file.
2. Start the container with the following command:

    ```sh
    docker-compose up
    ```

3. To stop the container, use the keyboard shortcut `Ctrl + C`.

### Usage

To connect to the database, use the following default credentials (you can change these if needed):

- **Username:** `mainuser`
- **Password:** `123456789`
- **Port:** `5432`
- **Volume:** `postgres_data:/var/lib/postgresql/data`

The first time you run this command, Docker will automatically download the necessary image. On subsequent runs, it will initialize the container without downloading the image again.
