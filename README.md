# Terraform-Multiple-Envs
Managing multiple environments like dev and prod with Terraform

Use this commands to run this : 
1. terraform init // to download providers
2. terraform workspace new dev // to select a workspace
3.terraform apply -var-file=dev.tfvars // passes the values in dev.tfvars file to main.tf
4.terraform workspace new prod // create a new workspace prod
5.terraform apply -var-file=prod.tfvars // passes the value in prod.tfvars to main.tf

Medium Link for code explanation : 

