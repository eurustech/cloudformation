# Cloud Formation Script to setup a sample aws cluster and NodeJs Application
This cloud formation script will setup an infrastructure with a VPC, 2 public subnets and 2 private subnets in AWS  environment. It will setup a mysql database in 2 private subnets and sample nodejs application in 2 public subnets with optional load balancing/autoscaling feature.

Following are the steps to be followed

### Step 1
Import vpc-template.yml stack
### Step 2
Import RDS-template.yml stack
### Step 3
#### With Autoscaling
Import EC2-template-Autoscaling.yml stack
#### Without Autoscaling
Import EC2-template.yml stack
