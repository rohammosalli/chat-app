

## Simple Chat application written in Go and gorilla WebSocket

#### Requirements
:warning: 

Go installed 

### Prepare development environment

```bash
go mod download
```
Build the code
```bash 
go build -o dist/server cmd/web/*.go
```

### Start working with the application 


Run the server
```bash
./dist/server 

# Then you should see the message
2022/11/14 18:57:37 Starting channel listener
```
