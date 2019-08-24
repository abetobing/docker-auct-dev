# JHipster generated Docker-Compose configuration

## Usage

Launch all your infrastructure by running: `docker-compose up -d`.

## Configured Docker services

### Service registry and configuration server:

- [JHipster Registry](http://localhost:8761)

### Applications and dependencies:

- AuctAuth (uaa application)
- AuctAuth's postgresql database
- AuctBid (microservice application)
- AuctBid's postgresql database
- AuctBid's elasticsearch search engine
- AuctCatalogue (microservice application)
- AuctCatalogue's postgresql database
- AuctCatalogue's elasticsearch search engine
- AuctGateway (gateway application)
- AuctGateway's postgresql database

### Additional Services:

- Kafka
- Zookeeper
- [JHipster Console](http://localhost:5601)
- [Zipkin](http://localhost:9411)
