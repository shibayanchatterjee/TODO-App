# TODO App
Application based on golang and react.

# Go Backend

## Install Go

1. Download the latest version of Go from the [official website](https://go.dev/dl/).
2. Follow the installation instructions for your operating system.
3. Set up your Go workspace by creating a directory for your Go projects, e.g., `~/go`.
4. Add the Go binary to your system's PATH environment variable.
5. Verify the installation by running `go version` in your terminal.
6. Set up your Go environment by creating a `go.mod` file in your project directory:
   ```bash
   go mod init github.com/yourusername/yourproject
   ```

## Version

```bash
go version
```

## Project Structure

```
.
├── cmd
│   └── main.go
├── internal
│   ├── handlers
│   │   └── handler.go
│   ├── models
│   │   └── model.go
│   └── services
│       └── service.go
├── pkg
│   └── utils
│       └── utils.go
├── go.mod
├── go.sum
└── README.md
```
   