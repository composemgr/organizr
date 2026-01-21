# Organizr

A self-hosted application for managing organizr.

## Installation

### Option 1: Quick Install
```bash
curl -q -LSsf "https://raw.githubusercontent.com/composemgr/organizr/main/docker-compose.yaml" | docker compose -f - up -d
```

### Option 2: Git Clone
```bash
git clone "https://github.com/composemgr/organizr" ~/.local/srv/docker/organizr
cd ~/.local/srv/docker/organizr
docker compose up -d
```

### Option 3: Using composemgr
```bash
composemgr install organizr
```

## Configuration

See docker-compose.yaml for environment variables and configuration options.

## Documentation

Check the official project documentation for detailed setup and usage information.
