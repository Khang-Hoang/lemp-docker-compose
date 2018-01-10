# Depoly lemp stack with docker-compose
## Usage
Clone my repository:
```sh
$ git clone git@github.com:Khang-Hoang/lemp-docker-compose.git
```

Goto lemp-docker-compose directory, type `docker-compose up` to build and run the app
```sh
$ cd lemp-docker-compose
$ docker compose up 
```
To start containers in detached mode
```sh
$ docker compose up -d
```

## Test the app
|       Virtual host    | Expected result |
| --------------------- | --------------- |
| http://localhost:8080 | phpinfo page    |
| http://localhost:8888 | phpmyadmin page |