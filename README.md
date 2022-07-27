# How to use docker compose

- The `docker-compose.yml` should be in the same folder as all other services
- Run `docker compose build`
- Run `docker compose up`
- `docker-compose-not-working.yml` has problems with RabbitMQ

### Hosts

- localhost

### Ports
- 8081: Frontend
- 8090: API-Gateway
- 9001: Warehouse
- 9002: ProductService
- 9003: PriceService
- 9004: CurrencyService

---
- 8080: Keycloak
- 5672 & 15672: RabbitMQ

### Keycloak

- First start Keycloak with `docker-compose up` (it may take a while)
- Log in at `localhost:8080` with username: admin, password: admin
- Click on "Users" on the left side, then click on "Add user" on the right
- Enter username "user" and click save
- Click on "Credentials" and set the password "user", turn off the "Temporary" Slider!
- Click on Role Mappings and add Role "user" to "Assigned Roles"