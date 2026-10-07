# Flask CRUD REST API

A RESTful API built with Flask for managing events. The project demonstrates
how to build backend endpoints that support creating, reading, updating, and
deleting resources using HTTP methods and JSON.

## Features

- Get all events
- Create a new event
- Update an existing event
- Delete an event
- Validate incoming JSON data
- Handle missing resources with `404 Not Found`
- Return appropriate HTTP status codes
- Automated API tests with Pytest
- In-memory data storage

## Tech Stack

- Python
- Flask
- REST API
- JSON
- Pytest
- Pipenv
- Git & GitHub

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/events` | Get all events |
| POST | `/events` | Create a new event |
| PATCH | `/events/<event_id>` | Update an event |
| DELETE | `/events/<event_id>` | Delete an event |

## Example Request

### Create an Event

```http
POST /events
Content-Type: application/json
