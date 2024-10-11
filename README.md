# VPC-with-servers-in-private-subnets-and-NAT
✅ Things Done:
1. To improve resiliency, deployed the servers in two Availability Zones, by using an Auto Scaling group and an Application Load Balancer.
2. For additional security, deployed the servers in private subnets. The servers receive requests through the load balancer.
3. The servers can connect to the internet by using a NAT gateway. To improve resiliency, deploy the NAT gateway in both Availability Zones.
