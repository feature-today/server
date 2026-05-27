# `feature-today/server`

**Status: placeholder** — currently the feature-today app (`my`) handles all backend logic via [QwikCity / Qwik Router](https://qwik.dev/docs/route-loader/) endpoints.

This repo exists as a reservation for the day we extract:

- background jobs that can't run on Vercel Edge,
- a long-lived WebSocket / SSE layer,
- shared API surface for multiple frontends.

If you are looking for the current API, see [`feature-today/my`](https://github.com/feature-today/my) (routes under `src/routes/api/*`).

## License

[AGPL-3.0-or-later](./LICENSE)
