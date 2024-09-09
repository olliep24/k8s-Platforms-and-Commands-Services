**Built in conjunction with**
- [Platform-Service](https://github.com/olliep24/Platforms-Service)
- [Command-Service](https://github.com/olliep24/Commands-Service)

This project contains all the Kubernetes configuration `.yaml` files needed to deploy my microservices project.

It deploys the following:
- [Platform service](https://github.com/olliep24/Platforms-Service)
- SQL Server database for the Platform service
- NodePort for the Platform service
- [Command service](https://github.com/olliep24/Commands-Service)
- RabbitMQ message broker
- Ingress-NGINX API gateway and load balancer
