# vprofile-aws
Hosting and Running Multi tier web application stack on AWS Cloud for production using the Lift & Shift strategy

## AWS Service Architecture
*  EC2 Instances: VM for TOMCAT, RABBITMQ, MEMCACHE, MYSQL
*  ELB [Load Balancer]: NGINX load balancer replacement
*  AutoScaling: Automation for VM Scaling
*  S3/EFS Storage: Shared Storage
*  Route 53: Private DNS Service
