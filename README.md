# AWS-Multi-Container
This is an unnecesary complex app, using 4 different services to showcase how to deploy a multi container app to AWS ElasticBeanstalk.
- Client: A React App consuming an API to show fibonacci numbers.
- API: The API to be consumed, made with Express.
- Worker: A service which calculates the value of the fibonacci number required, using a Redis instance in the AWS VPC Used, made with Express.
- Nginx: A reverse proxy to route request to the correct service.
