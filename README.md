# Repo managed by ShipLoop

Initial commit created by ShipLoop.

## API

Run the server with:

```
python3 app.py
```

### GET /version

Returns the current API version.

- **Method:** GET
- **Path:** `/version`
- **Status:** `200 OK`
- **Response body:** `{"version": "1.0.0"}` (`Content-Type: application/json`)

Any unmatched path returns `404 Not Found` with a JSON error body.
