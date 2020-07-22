```
1. Building: docker build <path> -t <app_name>

2. Run: docker run -p <any_port>:<app_port> -d <app_build_name>

### To run this app:
1. docker build . -t docker-express

2. docker run -p 8080:8080 -d docker-express // app starts at port 8080 background (as -d flag is specified).
```
