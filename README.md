# Heart 4 Mom

## Pre-requisites

Works with latest node versions.
The frontend is configured by default to use a test klinica.io api server (check in ./src/environments/environments.ts).

## Local development

Fetch dependencies:

```bash
npm install
```

Generate graphql client (should run this whenever the schema changes):

```bash
npm run graphql
```

Run locally:

```bash
npm start
```

The application can be accesed by navigating to `http://localhost:4200/`.

