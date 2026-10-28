# Create env variable

```
vim .env
```

```
DB_NAME=training
DB_HOST=ipaddress
DB_USER=peserta
DB_PASS=password
APP_PORT=3000
```

sonar-scanner \
 -Dsonar.projectKey=simple-apps \
 -Dsonar.sources=. \
 -Dsonar.host.url=http://172.23.13.92:9000 \
 -Dsonar.token=sqp_1592c5cfbe78b09c84b361bd8d8cb34389f0ec99
