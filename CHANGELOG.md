# Change Log

## [1.0.1](https://github.com/auth0/auth0-java-mvc-common/tree/1.0.1) (2018-06-13)
[Full Changelog](https://github.com/auth0/auth0-java-mvc-common/compare/1.0.0...1.0.1)

**Security**
- Use latest auth0-java, java-jwt and jwks-rsa libraries [\#11](https://github.com/auth0/auth0-java-mvc-common/pull/11) ([lbalmaceda](https://github.com/lbalmaceda))

## [1.0.0](https://github.com/auth0/auth0-java-mvc-common/tree/1.0.0) (2017-05-24)

Reworked the library to support both **Code Grant** and **Implicit Grant** authentication flows by using the latest [Auth0-Java](https://github.com/auth0/auth0-java/) SDK. 

The changes from v0 includes:

- Simpler setup and configuration
- Use of Auth0 Hosted Login page and OAuth 2.0 endpoints for Authentication
- Support **Code Grant** and **Implicit Grant** flows.
- Support Public Key Rotation when verifying Token signatures (Implicit Grant)
