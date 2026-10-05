# editalmind-contracts

Single source of truth for the contracts between [EditalMind](https://github.com/For-Davi/editalmind) services:

- **OpenAPI** specification of the core API, from which the web app generates its TypeScript types.
- **JSON Schemas** of the events exchanged through the queue (for example `edital.processed`).

Contracts are added as the endpoints and events are built, starting with the authentication routes. Changes are validated in CI (OpenAPI lint) and published as versioned packages for TypeScript and Python consumers.
