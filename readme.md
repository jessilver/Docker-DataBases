This is my repository where I will put my database connections using Docker.

## Getting Started

Follow these instructions to set up and run the database connections using Docker.

### Prerequisites

- Docker installed on your machine
- Basic knowledge of Docker and databases

### Installation

1. Clone the repository:
    ```
    git clone https://github.com/jessilver/Docker-DataBases.git
    ```
2. Navigate to the project directory:
    ```
    cd [the database that you want]
    ```
3. Build and run the Docker containers:
    ```
    docker-compose up --build
    ```
4. Stop the Docker containers:
    ```
    docker-compose down
    ```
5. Start the Docker containers:
    ```
    docker-compose start [service_name]
    ```
6. Remove the Docker containers:
    ```
    docker-compose rm [service_name]
    ```

### Usage

To connect to the database, use the following credentials:
- ### [Postgres](https://github.com/jessilver/Docker-DataBases/blob/main/Postgres/readme.md)
- ### [MySQL](https://github.com/jessilver/Docker-DataBases/blob/main/MySQL/readme.md)


### Contributing

Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvements.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Acknowledgments

- Thanks to all the contributors and open-source projects that made this possible.
- Special thanks to me for start this :D.

Happy coding!