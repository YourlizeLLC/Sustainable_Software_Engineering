# AWS Foundations

## Overview of AWS

### Cloud Computing Models
- IaaS vs Paas#
AWS offers both

#### Infrastructure as a Service (IaaS):
- allows organizations to utilize AWS instead of owning and operating their own datacenter. You can simply rent VMs or physical servers from AWS
- Amazon Web Services manages the Infrastructure for you. They own and operate the data center and give the user VMs and other services at a fractional cost to the user.

#### The Platform as a Service (PaaS)
- removes the need for your organization to manage the underlying platforms like a database, streaming services, etc. 
- allows you to focus on the deployment and management of your core applications and not worry about the IaaS and PaaS layers
- ets organizations to be more efficient and focused as you don’t need to worry about resource procurement, capacity planning, software maintenance, patching, or any of the other undifferentiated heavy lifting involved in running your application.

### AWS Infrastructure
Consists of four primary areas which are a combination of IaaS and PaaS:
CS Dentist

- Compute (EC2, LightSail, ECS, Lambda, Batch)
- Storage (EBS, EFS, S3, Glacier, Storage Gateway, Storage Migration Services)
- Database (RDS, Redshift)
- Network (CloudFront, VPC, Direct Connect, Load Balancing, Route 53)


#### Compute#
- Compute(EC2): create/deploy your own virtual machine. At AWS you have a wide variety of compute instances you can choose from. This ranges from the type of operating system you would choose to the RAM or CPU you would want your compute instance to have.

- Elastic Container Services(ECS):run and manage your Docker containers. think of it as a managed Kubernetes service.

- LightSail (VPS Service – Virtual Private service): AWS Lightsail launches virtual private servers, which are VMs with individual operating systems but restricted access to physical server resources.

- Lambda: Lambda lets you upload a function onto AWS and you pay every time the function is executed or called. You do not need to think about managing the OS or the VM.
