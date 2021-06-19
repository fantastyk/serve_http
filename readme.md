# Introduction 

This is a Go implementation of a quick HTTP server to a solve a problem with certain request types that I ran across with Python's SimpleHTTPServer. Please use a proper HTTP server for production use. 

# Example usage

To serve up the current directory on port 8081.
```bash
serve -p 8081
```

# Building
### Windows 
```bash
GOOS=windows GOARCH=amd64 go build -o serve main.go
```

### Linux
```bash
GOOS=linux GOARCH=amd64 go build -o serve main.go
```

### Mac
```bash
GOOS=darwin GOARCH=amd64 go build -o serve main.go
```
