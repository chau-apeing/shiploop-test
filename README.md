# Repo managed by ShipLoop

Initial commit created by ShipLoop.

## Running the app

Start the server (uses only the Python standard library, no dependencies to install):

```
python3 app.py
```

The server listens on `0.0.0.0:8000` by default. Set the `PORT` environment variable to use a different port:

```
PORT=9000 python3 app.py
```

## Testing the health check

With the server running, verify the `/healthz` endpoint:

```
curl http://localhost:8000/healthz
```

Expected output:

```
{"ok": true}
```

Any other path (e.g. `/`) returns a 404 status.
