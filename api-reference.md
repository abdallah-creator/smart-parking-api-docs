# API Reference

Below is a summary of the main endpoints exposed by the Smart Parking System API.

## 1. Get Available Parking Spots

**Endpoint:** `GET /api/v1/parking-spots/available`  
**Query Parameters:**
- `latitude` (required)
- `longitude` (required)
- `radius` (optional, default: 500m)

**Response:**
```json
[
  {
    "id": "123",
    "zone": "Zone A",
    "lat": 24.7136,
    "lng": 46.6753,
    "price_per_hour": 3.00,
    "status": "available"
  }
]
