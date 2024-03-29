# Como rodar local

```bash
docker-compose up --build
```

```bash
curl -X POST http://localhost:8081/cep \
     -H "Content-Type: application/json" \
     -d '{"cep":"29902555"}'
```

# Acessar o [Zipkin](http://localhost:9411/zipkin/)