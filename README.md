
# Docker Node.js App

This is a simple Node.js application designed to run inside a Docker container.

## Steps to Run

1. Build Docker image:
   ```
   docker build -t yourusername/docker-node-app:latest .
   ```
2. Run Docker container:
   ```
   docker run -p 3000:3000 yourusername/docker-node-app:latest
   ```
