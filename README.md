<h1 align="center">Laravel-React Test</h1>

## Introduction

This guide will help you install and set up a Laravel project using Docker.

## Prerequisites

-   Docker (version 24.0.1)
-   Docker Compose (version 2.12.2)
-   Composer (version 2.5.5)
-   PHP (version 8.2.6)
-   Node.js (version 16.15.1)
-   npm (version 8.11.0)

## Installation

1. Clone the project repository:

    ```bash
    git clone https://github.com/ksmks0921/Assessment-Innosripta-Full.git

    ```

2. Navigate to the project directory:

    ```bash
    cd Assessment-Innosripta-Full

    ```

3. Start the Docker containers:

    ```bash
    docker-compose up -d

    ```

4. Visit:

    Visit http://127.0.0.1:8000 in your browser to access the Laravel pplication.
    Visit http://127.0.0.1:5173 in your browser to access the React application.

## Additional Information

The Docker configuration is defined in the docker-compose.yml file.
The database configuration can be modified in the .env file.

## Troubleshooting

If you encounter any issues, please ensure that you have the required software versions mentioned in the prerequisites section.
For more detailed troubleshooting steps, refer to the Laravel and Docker documentations
