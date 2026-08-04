# Socky

MCP configuration project using mixsource Docker image.

## Setup

1. Copy `.env.example` to `.env` and configure as needed
2. Run `docker-compose up -d`
3. Access the service at `http://localhost:3000`

## Configuration

MCP configurations are stored in the `/mcp` directory.

## Project Structure

```
socky/
├── mcp/              # MCP configuration files
├── config/           # Application configuration
├── docker-compose.yml
└── README.md
```
