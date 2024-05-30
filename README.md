# Terraform
This is a repo in which simple tasks like creating an AWS instance is added
first and foremost configure the aws cli using the aws configue command, give the access key and the secret access key

//install terraform, here I downloaded the terrafirn for windows and extracted teh .exe file. And maintained te path in environment variables
in a folder create the main.tf with the content given

run terraform init , to initaliaze the terraform like this will install the dependencies like plugins, etc
post that make a dry run, using terraform plan
if all good, then run the exuecution using terraform apply

Post everything done run the terraform destroy to unistall the dependencies installed in the init cmd
