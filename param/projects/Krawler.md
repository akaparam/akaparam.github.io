# Krawler - THE OSS URL SHORTNER

An open source serverless URL shortener built using AWS SAM, Lambda, API Gateway, and DynamoDB (single-table design) for the backend and React/Tailwind UI for the frontend. The API allows for CRUD operations, seamless redirects, analytics for your generated URLs, custom slugs for URL redirection, support for temporary URLs with TTL fields, password protected URLs and much more.

It is a monorepo with the following folder structure:

- `api/`: AWS SAM + Lambda + DynamoDB backend
- `ui/`: Vite + React + Tailwind frontend
- `docs/`: API, architecture, deployment, and testing docs

## Repository Layout

```text
.
├── api/
│   ├── src/
│   ├── tests/
│   ├── template.yaml
│   ├── samconfig.toml
│   └── package.json
├── ui/
│   ├── src/
│   ├── .env.example
│   └── package.json
├── docs/
├── Makefile
└── README.md
```

## Documentation

- [Architecture & Data Model](docs/overview.md)
- [API Reference](docs/api.md)
- [Deployment & Operations](docs/deployment.md)
- [Testing](docs/testing.md)

**GitHub URL**: https://github.com/akaparam/krawler.git