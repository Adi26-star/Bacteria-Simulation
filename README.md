# Bacteria Simulation Test Server

This repo contains `test.html` and instructions to serve it with Python's built-in HTTP server.

## Requirements
- Python 3

## Quick start
1. From the repo root, run:
   ```bash
   python -m http.server 8888
   ```
2. Open your browser to:
   ```
   http://localhost:8888/test.html
   ```

## Notes
- The server serves the current directory, so `test.html` is available at `/test.html`.
- Stop the server with `Ctrl+C`.
