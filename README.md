# Edgar Lens OpenAPI Specification

## Overview
This repository contains the **OpenAPI specification** for the Edgar Lens API, plus example requests, error codes, and changelog.

The API exposes:
- AI-powered semantic diffs of SEC filings
- Red-flag detection (risk factor changes, restatements, auditor changes)
- Sourced Q&A over filings
- Watchlists & alerts

## View the Spec
The latest spec is in [`openapi.yaml`](openapi.yaml).

## Quick Start
```bash
curl -X POST "https://api.edgarlens.com/v1/diff" \
  -H "Authorization: Bearer YOUR_API_KEY" \
  -H "Content-Type: application/json" \
  -d '{"ticker":"AAPL"}'
```

## SDKs
- JavaScript/TypeScript: https://github.com/edgarlens/sdk-js
- Python: https://github.com/edgarlens/sdk-python

## Docs
Once live: https://docs.edgarlens.com

## Contributing
Open an issue for questions or proposed changes to the spec. See `CONTRIBUTING.md`.

## License
Apache License 2.0 — see [LICENSE](LICENSE).
