# ALX Travel App API

## API Endpoints

### Listings
- `GET /api/listings/` - List all active listings
- `POST /api/listings/` - Create new listing (authenticated)
- `GET /api/listings/{id}/` - Retrieve specific listing
- `PUT /api/listings/{id}/` - Update listing (owner only)
- `DELETE /api/listings/{id}/` - Delete listing (owner only)

### Bookings
- `GET /api/bookings/` - List user's bookings (authenticated)
- `POST /api/bookings/` - Create new booking (authenticated)
- `GET /api/bookings/{id}/` - Retrieve specific booking
- `PUT /api/bookings/{id}/` - Update booking (owner only)
- `DELETE /api/bookings/{id}/` - Cancel booking (owner only)

## Authentication
- Basic Auth or Session Auth required for write operations

## Documentation
- Swagger UI: `/swagger/`
- ReDoc: `/redoc/`

## Testing with Postman
1. Import the Postman collection from `docs/postman_collection.json`
2. Set base URL to your development server
3. For protected endpoints, add Basic Auth header
