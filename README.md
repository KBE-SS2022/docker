# How to use docker compose

- The `docker-compose.yml` should be in the same folder as all other services
- Run `docker compose build`
- Run `docker compose up`

### Ports
- 8080: Warehouse
- 8081: ProductService
- 8082: CurrencyService
- 8083: PriceService
---
- 5672 & 15672: RabbitMQ