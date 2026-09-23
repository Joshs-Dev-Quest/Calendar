# Freezed Requirements for the module

## Endpoints
The calendar application must have the following endpoints:

| HTTP Method | Endpoint | Description |
| ----------- | -------- | ----------- |
| `GET` | `/api/health` | Returns health status without database |
| `GET` | `/api/ready` | Returns readiness status with database |
| `GET` | `/api/metrics` | Prometheus metrics scrape endpoint |
| `POST` | `/api/event` | Create a new event |
| `DELETE` | `/api/event/<id>` | Delete an event |
| `POST` | `/api/update/<id>` | Update an event |
| `GET` | `/api/event/<id>` | Get an event |
| `GET` | `/events?from=...&to=...` | List events in a time range |
