# BED Server

This project contains configurations, scripts, and resources to set up and manage our Minecraft server using PaperMC. The repository is structured to streamline the process of downloading, configuring, and running our Minecraft server with minimal effort.

## Features

- **Automated Setup**: Scripts to download and configure the latest PaperMC jar.
- **World Management**: Unzipping worlds.
- **Pre-configured Files**: Essential server configurations ready to use.
- **Easy Server Management**: Script to start the server effortlessly.
- **Docker Compose Support**: Simplifies deployment with Docker, including production setup.

## Prerequisites

Before you begin, ensure you have installed on your system the following requirements:

- **bash**: Required for running the scripts.
- **Java**: The server requires Java 21 or higher.
- **wget**: Required for downloading files in the scripts.
- **unzip**: Required for extracting downloaded worlds.
- **Docker**: Required for running the Docker container.
- **Docker Compose**: Required for managing Docker containers.

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/beduality/server.git
    cd server
    ```

2. **Run the Setup Script**

    Execute the setup script to download the PaperMC jar and unzip the worlds:

    ```bash
    bash ./scripts/prepare.sh
    ```

## Usage

### Development Mode

To start the server in development mode, run the following script:

```bash
bash ./scripts/dev.sh
```

### Production Mode

To start the server in production mode using Docker Compose, run the following command:

```bash
docker compose up -d
```

To stop the server in production mode, use:

```bash
docker compose down
```
