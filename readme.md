# QR Code API

A simple FastAPI app to create, list, and delete QR codes.

---

## Features

- Login with token
- Create QR codes from URLs
- View and delete saved QR codes

---

## How to Run

```bash
uvicorn app.main:app --reload
```

---

## Testing

```bash
pytest
```

---

## Docker

```bash
docker build -t qr-api .
docker run -p 8000:8000 qr-api
```
