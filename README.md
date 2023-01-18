# Build Reactive Java Microservices with Spring Boot and JHipster

Tutorial from Matt Raible

[Reactive Java Microservices with Spring Boot and JHipster](https://developer.okta.com/blog/2021/01/20/reactive-java-microservices)

[Youtube](https://www.youtube.com/watch?v=clkEUHWT9-M&list=PLshTZo9V1-aEOJ2gkvvF0CY63H7IlM0lx&index=5)

### Okta config

- from `gateway` folder run
    - `okta apps create jhipster`
    - name: `Reactive Microservices`
    - redirect URIs: default
    - post logout redirect URIs: default
- modify `gateway/src/main/docker/central-server-config/localhost-config/application.yml`
    - change OIDC config