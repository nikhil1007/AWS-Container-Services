# AWS-Container-Services
Fargate, Cloudformation

The Cloudformation Template attached does the following :

- Creates all the required resources like : Task Definition, ECS cluster, ECS service, Load Balancer etc..
- Takes care of the Networking aspects like, creation of VPC, subnets etc.. and updating the Route Tables with appropriate routes
- Outputs the DNS name of the load balancer through which you can access the sample application
