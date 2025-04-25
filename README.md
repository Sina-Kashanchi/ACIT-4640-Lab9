# 4640-w9-lab-start-w25

### Commands to import key to AWS:

1. `ssh-keygen -t ed25519 -f ~/.ssh/aws` to create a new SSH key pair named **aws**
2. `./scripts/import_lab_key ~/.ssh/aws.pub` to import the key to the AWS account

### Commands to create AMI using Packer:

1. `cd packer` to go into the packer directory
2. `packer init .` to install required plugins
3. `packer validate .` to check if there are errors in configuration files
4. `packer build .` to build the image

### Commands to create EC2 instance using Terraform

1. `cd terraform` to go into the terraform directory
2. `terraform init` to install required providers
3. `terraform validate` to check if there are errors in configuration files
4. `terraform apply` to create the EC2 instance

### Screenshots

![img](./Lab9.jpg)
![img](./Lab9-1.jpg)
