# README for Docker Setup

## Quick Start

1. **Build the Docker Image:**
   ```bash
   docker build -t my-node-app .
   ```

2. **Run the Container:**
   ```bash
   docker run -d -p 3040:3040 --name my-running-app my-node-app
   ```

3. **Access the App:**
   Visit [http://localhost:3040](http://localhost:3040) in your browser.

## Common Commands

- **Stop the Container:**
   ```bash
   docker stop my-running-app
   ```

- **Remove the Container:**
   ```bash
   docker rm my-running-app
   ```

## Notes

- The app runs on port `3040`.
- Adjust the port in the Dockerfile or run command if needed.

That's it!
