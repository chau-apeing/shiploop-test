# Repo managed by ShipLoop

Initial commit created by ShipLoop.

## Running the server

Start the server with:

```
python app.py
```

The server listens on port 8000.

### Endpoints

- `GET /ping` — returns HTTP 200 with `Content-Type: text/plain` and body `pong`.
- Any other path returns HTTP 404.

Verify with curl:

```
curl -i http://localhost:8000/ping
```
