# ConsoleKeyStore

docker run --name keycloak -p 8080:8080 -e KEYCLOAK_USER=admin -e KEYCLOAK_PASSWORD=admin jboss/keycloak

Create a realm 'test'

Create a client app 'demo-app'

Use http://localhost:8080/auth/realms/test/.well-known/openid-configuration to see endpoints

Based on https://github.com/IdentityModel/IdentityModel.OidcClient
