# Frameworks and Languages Module
Stub framework for "Frameworks and Languages" module

## Instructions
### 1. Making Server
```cmd
cd server
make build
make run
```
This should start the Server.

### 2. Making Client
```cmd
cd server 
make build
make run
```
This should start the Client.
### 3. Running test on server
```cmd
# in the main directory
make test_server
```

### 4. Running test on client
```cmd
    # ADMIN
    choco install nodejs
    # in test_client dir
    npm install cypress
    npx cypress open --e2e --browser chrome
    # always fails on first installed run
```


https://gitpod.io/#https://github.com/calaldees/frameworks_and_languages_module

* [ReDoc openapi.yml](https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/calaldees/frameworks_and_languages_module/main/openapi.yml)
