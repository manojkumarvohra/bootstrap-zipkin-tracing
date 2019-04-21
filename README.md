# bootstrap-zipkin-tracing
Distributed Tracing Example using Zipkin and Sleuth

# Configuration
- zipkin server is started here as embedded with spring boot application with port as 8888
- zipkin clients are configured to point their zipkin traces and spans to this server and port (8888)

# How to use
- Build the project
- Start the boot applications individually
- Monitor traces & spans @ <host/localhost>:8888 for a journey
# References
- For custom spans and async spans examples see: https://github.com/eugenp/tutorials/tree/master/spring-sleuth
