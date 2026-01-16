# Bacteria Simulation Test Server

This repo contains `test.html` and a helper script to serve it with Python's built-in HTTP server.

## Requirements
- Python 3

## Quick start
1. From the repo root, run:
   ```bash
   ./run_test_server.sh
   ```
2. Open your browser to:
   ```
   http://localhost:8000/test.html
   ```

## Custom port
To use a different port:
```bash
./run_test_server.sh 9000
```
Then visit:
```
http://localhost:9000/test.html
```

## Notes
- The server serves the current directory, so `test.html` is available at `/test.html`.
- Stop the server with `Ctrl+C`.
