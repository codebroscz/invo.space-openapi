# invo.space API Docs

## Changelog

### 1.3.2025

- endpoints returning collections now have `limit` and `offset` query parameters
- endpoints returning collections now wrap resource objects to `data` field and have `total` field in response body

### 28.2.2025

- removed field `status` from `CreateDocumentResponse` schema snippet
- `CreateDocumentResponse` schema snippet renamed to `DocumentIdentificationResponse`
- added `PATCH` and `PUT` methods to `/invoices/{id}` endpoint
- request schema for creating DocumentItems is simplified
