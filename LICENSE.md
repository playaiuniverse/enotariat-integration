# eNotariat Integration (QR Verification & Webhooks)

> Starter pack for integrating with the Unified Registry of Powers of Attorney (ЄРД): OpenAPI, webhook schemas, Postman collection, and examples.

## Structure
```
api/      - OpenAPI 3.1 spec
events/   - JSON Schemas for webhook events
examples/ - Postman collection & cURL helpers
docs/     - Integration diagram (PNG)
```

## Quick Start
1. **Import API**: `api/enotariat-openapi.yaml` into your API Gateway or Swagger UI.
2. **Run requests**: Import `examples/enotariat-postman.json` into Postman.
3. **Validate webhooks**: Use schemas from `events/` in your webhook receiver.
4. **Try with cURL**: See `examples/enotariat-curl-examples.txt`.

## Suggested Repo Name
`enotariat-integration` or `govassist-enotariat`

Generated: 2025-08-14T19:13:21.737997Z
