# terraform

# Readme
This is a tutorial to install terraform


# Installation

## connect to ssh server

ssh -i "key1.pem" ubuntu@ec2-13-239-1-63.ap-southeast-2.compute.amazonaws.com

## download

wget https://releases.hashicorp.com/terraform/0.12.7/terraform_0.12.7_linux_amd64.zip

## move install files

#ubuntu@ip-172-31-6-200:~/terraform$ sudo mv terraform /usr/local/bin/

# check version
ubuntu@ip-172-31-6-200:~/terraform$ terraform --version

Terraform v0.12.7

# initialise
ubuntu@ip-172-31-6-200:~/terraform$ terraform init

#create user account on AWS

#temporary key created for testing only

#Access key ID

#************


# run test
ubuntu@ip-172-31-6-200:~/terraform$ terraform plan

# run implement
ubuntu@ip-172-31-6-200:~/terraform$ terraform apply

# run remove
ubuntu@ip-172-31-6-200:~/terraform$ terraform destoy
