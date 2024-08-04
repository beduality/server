# BED Server

This project contains configurations, scripts, and resources to set up and manage our Minecraft server using PaperMC. The repository is structured to streamline the process of downloading, configuring, and running our Minecraft server with minimal effort.

## Features

- **Automated Setup**: Scripts to download and configure the latest PaperMC jar.
- **World Management**: Unzipping worlds.
- **Pre-configured Files**: Essential server configurations ready to use.
- **Easy Server Management**: Script to start the server effortlessly.

## Prerequisites

Before you begin, ensure you have installed on your system the following requirements:

- **bash**: Required for running the scripts.
- **Java**: The server requires Java 21 or higher.
- **wget**: Required for downloading files in the scripts.
- **unzip**: Required for extracting downloaded worlds.

## Installation

1. **Clone the Repository**

    ```bash
    git clone https://github.com/beduality/server.git
    cd server
    ```

2. **Run the Setup Script**

    Execute the setup script to download the PaperMC jar and unzip the worlds:

    ```bash
    ./scripts/prepare.sh
    ```

## Usage

### Setup

To start the Minecraft server, run the following script:

```bash
./scripts/start.sh
```

### Stopping the Server

To stop the server gracefully, you can use the stop script:

```bash
./scripts/stop.sh
```
