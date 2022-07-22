# How to use docker compose

- The `docker-compose.yml` should be in the same folder as all other services
- Run `docker compose build`
- Run `docker compose up`

### Ports
- 9000: API-Gateway
- 9001: Warehouse
- 9002: ProductService
- 9003: PriceService
- 9004: CurrencyService

---
- 5672 & 15672: RabbitMQ