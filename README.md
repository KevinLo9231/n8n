# n8n Development Environment

This project sets up a development environment for n8n using Visual Studio Code DevContainers.

## Prerequisites

- Docker
- Visual Studio Code
- Dev Containers extension for Visual Studio Code

## Getting Started

1. Clone this repository to your local machine.
2. Open the repository in Visual Studio Code.
3. When prompted, reopen the repository in the DevContainer.
4. The DevContainer will automatically install n8n and set up the environment.
5. Once the DevContainer is running, you can access the n8n UI at `http://localhost:5678`.

## Features

- **Node.js 16**: The container uses Node.js 16 as the runtime environment.
- **n8n**: n8n is installed globally in the container.
- **Port Forwarding**: Port 5678 is forwarded to the host machine for accessing the n8n UI.
- **VS Code Extensions**: Docker and ESLint extensions are installed in the container for better development experience.

## Customization

You can customize the development environment by modifying the files in the `.devcontainer` directory.
