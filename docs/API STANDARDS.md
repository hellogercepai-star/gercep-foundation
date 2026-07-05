# GercepAI API Standards

## Principles

- RESTful Design
- JSON Response
- Secure by Default
- Versioned APIs

---

## Authentication

Bearer Token

---

## Response Format

Success

{
  "success": true,
  "data": {}
}

Error

{
  "success": false,
  "message": ""
}

---

## HTTP Status

200 OK

201 Created

400 Bad Request

401 Unauthorized

403 Forbidden

404 Not Found

500 Internal Server Error
