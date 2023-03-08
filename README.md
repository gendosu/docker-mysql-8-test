
### build

```
docker buildx build --target app -t gendosu/mysql-8-test:8.0.28 --platform linux/amd64,linux/arm64 -f Dockerfile --push .
```
