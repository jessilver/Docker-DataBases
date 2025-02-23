# MySQL

MySQL is a powerful, open-source relational database management system known for its reliability, feature robustness, and performance.

## Running MySQL with Docker

To run a MySQL container using Docker, follow these steps:

1. Navigate to the directory containing your `docker-compose.yml` file.
2. Start the container with the following command:

    ```sh
    docker-compose up
    ```

3. To stop the container, use the keyboard shortcut `Ctrl + C`.

### Usage

To connect to the database, use the following default credentials (you can change these if needed):

- **Username:** `root`
- **Password:** `1`
- **Port:** `3306`
- **Volume:** `mysql_data:/var/lib/mysql`

The first time you run this command, Docker will automatically download the necessary image. On subsequent runs, it will initialize the container without downloading the image again.
