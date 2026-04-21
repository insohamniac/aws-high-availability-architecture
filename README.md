# aws-high-availability-architecture
Highly available AWS architecture using Load Balancer, Auto Scaling Group, EC2, and RDS
This project demonstrates a highly available and scalable AWS architecture.
It uses an Application Load Balancer to distribute traffic across multiple EC2 instances running in an Auto Scaling Group.
The architecture ensures fault tolerance by automatically replacing unhealthy instances and maintaining application availability.
A private RDS database is used for secure data storage, accessible only within the VPC through security group rules.
