# railway-api

Sovereign HTTP proxy for **Railway** · exposes SDK methods over REST.

## Endpoints
- `GET /` — metadata + available methods
- `GET /health` — health check
- `POST /call/:method` — invoke SDK method with JSON body as params

## Env
`RAILWAY_API_KEY` required.

## Run
```bash
npm install && npm start
```

MIT · AI-Native Solutions estate.
