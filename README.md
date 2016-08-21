# ocr-hystrix-dashboard
Hystrix Dashboard for OCR Spring Cloud demo from my [blog](http://ryanjbaxter.com).  This project utilizes [Spring Cloud Netflix
to provide the Hystrix Dashboard](http://cloud.spring.io/spring-cloud-static/spring-cloud.html#_circuit_breaker_hystrix_dashboard).

## Running
This is a simple Spring Boot app which can be run easily just by cloning the repo.

```
$ git clone https://github.com/ryanjbaxter/ocr-hystrix-dashboard
$ cd ocr-hystrix-dashboard
$ ./mvnw spring-boot:run
```

Alternatively you can run the application using Docker.  There is a 
[Docker image](https://hub.docker.com/r/ryanjbaxter/ocr-hystrix-dashboard/) published to Docker Hub.

```
$ docker run -p 8383:8383 -i ryanjbaxter/ocr-hystrix-dashboard
```
