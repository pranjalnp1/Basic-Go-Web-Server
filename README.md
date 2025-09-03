# Basic Go Web Server

A beginner-friendly project to learn Go (Golang) and basic web development.

## Features

- **Serve Static Files:** Files in `static/` are served at `/`.
- **Hello Handler:** `GET /hello` responds with a greeting.
- **Form Handler:** `POST /form` displays submitted `name` and `address`.

## Project Structure

basic-go-web-server/
├── main.go # Sets up routes and starts the server
├── go.mod # Go module file
└── static/ # Static assets (HTML, CSS, JS, images, etc.)


### Routes

- `/` — Serves static files
- `/hello` — Returns "hello!"
- `/form` — Handles form submissions

## Getting Started

### Prerequisites

- [Go 1.16+](https://golang.org/dl/)
- Git

### Setup
git clone https://github.com/yourusername/Basic-Go-Web-Server.git
cd Basic-Go-Web-Server
go mod init basic-go-web-server  # Run only if not already initialized
go run main.go
go build

Usage
Open http://localhost:8080/ to access static files
Visit http://localhost:8080/hello to see a greeting
Submit a form to http://localhost:8080/form to view submitted data

Learning Goals
Understand HTTP routing in Go
Serve static files
Handle GET and POST requests
Use Go’s net/http standard library



