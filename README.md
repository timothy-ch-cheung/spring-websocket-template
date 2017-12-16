# spring-websocket-template

Provides a template for [spring](https://spring.io/) websocket usage (with and without SockJS support)

The project provides 2 modules:

* `without-sockjs`: Plain websocket integration with [Spring Boot](https://projects.spring.io/spring-boot/)
* `with-sockjs`: Websocket integration with [Spring Boot](https://projects.spring.io/spring-boot/) for backend and [React](https://reactjs.org/) for frontend. Checkout [README](with-sockjs/README.md) for more information

## Installation

```
mvn install && (cd with-sockjs && npm install)
```

## Issues

Report any issues or bugs to https://github.com/lahsivjar/spring-websocket-template/issues Pull requests are welcomed.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
