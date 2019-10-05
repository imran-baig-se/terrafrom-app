# terrafrom-app



This is a example terraform template to build vpc and install NGINX on ec2 and RDS DB with This template will create following resources.

   1. VPC
   2. Public Subnet - 1
   3. Private Subnet - 2
   4. Internet Gateway
   5. NAT Gateway
   6. Route Tables
   7. ELB
   8. Security Groups
   9. Bastion Host/ Jump Server
   10. EC2 Instances
   11. Install NGINX
   12. Attach Instances to ELB
   13.Create RDS DB (Postgress)
   14.Attache security group of ec2




### Steps to run
### Clone the git repo
```bash
git clone git@github.com:imran-baig-se/terraform-new.git
```
#### Run
```
cd <path to .tf file>
terraform init
terraform plan
terraform apply
```
