# Media Stack (Docker Compose)

A portable, host-agnostic Docker Compose setup for managing movies, shows, downloads, and media requests.

## Services

- 📽️ **Radarr** – Movies  
- 📺 **Sonarr** – TV Shows  
- 🔍 **Prowlarr** – Indexers  
- 🎟️ **Jellyseerr** – Requests UI  
- 🧲 **Deluge** – Downloader  
- 🧩 **FlareSolverr** – Anti-bot bypass  
- 🤖 **Radarr Telegram Bot** – Telegram notifications

## Quick Start

```bash
cp .env.example .env         # Set your environment variables
./init-folders.sh            # Create folders
docker compose up -d        # Launch services


