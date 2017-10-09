# CouchDB with proxy authentication

Follow the [instructions for the official CouchDB image](https://hub.docker.com/_/couchdb).

## Additional configuration

| Variable                   | Description |
| -------------------------- | ------------------------------------------------- |
| `COUCHDB_SECRET`           | The secret token is used for Proxy Authentication |
| `COUCHDB_PROXY_USE_SECRET` | Defaults to true, disabling is not recommended    |
