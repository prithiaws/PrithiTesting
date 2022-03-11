I have prepared terraform script where it can build 3-tier architecture layers (DB, App, Web). It includes network setup VPC as well.

Please find below information in detail:


1. VPC : (6 subnets)
2. IGW,Route table(for web level) 
3. Application load balancer (lb name, lb group, listener)
4. 3 - SG's 
5. EC2 Machines (2-db, 2-web, 2-app)

To test:

Ensure provide your aws access key, secret access key & have sufficient privileges on resources.

export AWS_ACCESS_KEY_ID=*************
export AWS_SECRET_ACCESS_KEY=****************



1. terraform init
2. terraform validate
3. terraform fmt
4. terraform plan
5. terraform apply
6. terraform destroy
