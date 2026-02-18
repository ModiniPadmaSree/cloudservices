Cloud Command Line Tools \
Command-line tools allow developers and administrators to manage cloud resources efficiently through scripts and automation.
1. AWS CLI \
Amazon Web Services CLI is a unified tool to manage AWS services from the terminal. It supports resource provisioning, monitoring, automation, and scripting. \
Steps to use AWS CLI
- Install aws cli - sudo apt install awscli
- Configure using keys - aws configure
- Run commands - aws ec2 describe-instances
2. Azure CLI \
Microsoft Azure CLI enables management of Azure resources via command line. \
Steps \
- Login - az login
- Create VM - az vm create --name myVM --resource-group myRG --image UbuntuLTS
3. Google Cloud SDK \
Google Cloud Platform SDK includes the gcloud CLI tool for managing GCP resources. \
Steps
- Initialize - gcloud init
- Commands - gcloud compute instances list
