# BreezeBox 🌤️

BreezeBox is a modern, live weather web application containerized with Podman.  
It fetches real-time weather data from OpenWeatherMap API and displays it in a stylish glassmorphic interface.

## Features
- Live weather updates for any city
- Responsive, glassy UI
- Containerized using Podman
- Easy to run anywhere

## Tools Used

- Linux (WSL2)
- Python & Flask
- Podman
- OpenWeatherMap API

## Demo
Pull and run the container:
```bash
podman pull docker.io/nithishak310806/breezebox:latest
podman run -p 5000:5000 docker.io/nithishak310806/breezebox:latest
