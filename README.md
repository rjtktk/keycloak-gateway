# keycloak-gateway
Keycloak Gateway

### Prerequisite

Docker

### How to run

1. Open terminal and go to keycloak-gateway folder.
2. Run `docker-compose up -d`
3. Get the port by calling `docker ps` and look for `keycloak-gateway-apisix`
4. Login to https://gladiator-keycloak-test.mooo.com/realms/bank-of-carnera/account/#/ to get access token
5. Pass that token as Bearer token while calling endpoint in Gateway Test postman collection