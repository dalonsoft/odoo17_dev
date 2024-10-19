# odoo17
Odoo 17 development enviroment using docker containers

### Disclaimer
This repository is intended for development and testing purposes only. It is not recommended to use this setup in a production environment.

### Creating a .env File

To create a `.env` file from the example file, follow these steps:

1. Copy the example file:
    ```sh
    cp .env.example .env
    ```

2. Open the `.env` file in a text editor and configure the parameters as needed.

#### Parameters Description

- `POSTGRES_DB`: The name of the PostgreSQL database
- `POSTGRES_USER`: The username for the PostgreSQL database
- `POSTGRES_PASSWORD`: The password for the PostgreSQL database
- `POSTGRES_EXPOSED_PORT`: The port on which the PostgreSQL database will be exposed.

Make sure to replace the placeholder values with the actual configuration for your environment.

Remember to keep the `.env` file private and never commit it to a public repository.

```

### Starting the Odoo 17 Development Docker Environment

To start the Odoo 17 Development Docker environment, run the following command:

```sh
docker-compose up -d
```

This command will start the Odoo 17 server and PostgreSQL database server in the background.

### Stopping the Odoo 17 Development Docker Environment

To stop the Odoo 17 Docker environment, run the following command:

```sh
docker-compose down
```

This command will stop and remove the Odoo 17 server and PostgreSQL database containers.