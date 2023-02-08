# expose
Demo Project to showcase following tech stack in sync:
1. Postgresql as "Database"
2. Springboot as "Framework"
3. Redis as "Cache"
4. Thymeleaf as "Template Framework"
5. MyBatis as "Spring ORM"
6. Datadog as "Observability"
7. Log4j2 as "Logging"

This project expose postgresql data via REST API in JSON Format.
Redis is used as cache for fast response with the API.
Frontend integration with the API.
Finally logging with log4j2 and observe and monitor using Datadog

Deployment:
First the application will be deployed on AWS ElasticBeanStack.

second option:
The application will be deployed on ECS with fargate as launch type.

Both scenario all components will be services - Database, backend, logging and monitoring



