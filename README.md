# Config

```yml
server:
  port: 8080
  allowOrigins:
    - "*"
  bodyLimit: "10M" # MiB
  timeout: 30 # Seconds
  
server:
  port: 8080
  allowOrigins:
    - "*"
  bodyLimit: "10M" # MiB
  timeout: 30 # Seconds
  
redis:
  host: localhost
  port: 6379

database:
  host: localhost
  port: 3306
  user: root
  password: 123456
  dbname: mydb
```