# Spring Cloud Eureka Server Getting Started

Eureka Server holds the information about all client-service applications, which is applications' port and IP address. Every application registers int the Eureka server.

## Description
### Dependency
- spring-cloud-starter-netflix-eureka-server

### Related Repository

- https://github.com/shinyay/spring-cloud-getting-started
- https://github.com/shinyay/spring-cloud-gateway-gs
- https://github.com/shinyay/spring-cloud-loadbalancer-gs
- https://github.com/shinyay/spring-cloud-config-gs
- https://github.com/shinyay/spring-cloud-config-client-gs

### Enable Spring Cloud Eureka Server
```kotlin
@SpringBootApplication
@EnableEurekaServer
class SpringCloudEurekaServerGsApplication
```

### Eureka Configuration

- eureka.client
  - `register-with-eureka`
    - Flag for registering its self to Eureka
  - `fetch-registry`
    - Flaf for fetching the Eureka registry

|property|value|
|--------|-----|
|service-url.defaultZone|http://localhost:${server.port}/eureka|
|register-with-eureka|false|
|fetch-registry|false|

## Demo

## Features

- feature:1
- feature:2

## Requirement

## Usage

## Installation

## Licence

Released under the [MIT license](https://gist.githubusercontent.com/shinyay/56e54ee4c0e22db8211e05e70a63247e/raw/34c6fdd50d54aa8e23560c296424aeb61599aa71/LICENSE)

## Author

[shinyay](https://github.com/shinyay)
