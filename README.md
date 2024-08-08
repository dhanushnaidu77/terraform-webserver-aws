AWS Infrastructure Setup with Terraform

This Terraform configuration script sets up a basic AWS infrastructure including a VPC, internet gateway, route table, subnet, security group, network interface, Elastic IP, and an EC2 instance. The instance is configured to serve a simple web page using Apache.

Key features:

VPC Creation: Creates a VPC with a CIDR block of 10.0.0.0/16.
Internet Gateway & Route Table: Sets up an internet gateway and associates it with a route table for internet access.
Subnet: Provisions a subnet within the VPC.
Security Group: Configures a security group to allow inbound traffic on HTTP, HTTPS, and SSH ports.
Network Interface: Attaches a network interface with a specific private IP to the EC2 instance.
Elastic IP: Associates an Elastic IP with the network interface.
EC2 Instance: Launches an EC2 instance with Apache installed, serving a simple web page.
