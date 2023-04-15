# Dockerfile of All DevOps tools
# Ansible
## How to use it?
### Build:
docker build -t ranjitswain/ansible:1.0 -f /home/ec2-user/Dockerfile.ansible .
### Run:
docker run -it --name mbansible ranjitswain/ansible:1.0
#Terraform
## How to use it?
### Build:
docker build -t ranjitswain/terraform:1.0 -f /home/ec2-user/Dockerfile.terraform .
### Run:
docker run -it --name terraform ranjitswain/terraform:1.0
#Git
## How to use it?
### Build:
docker build -t ranjitswain/git:1.0 -f /home/ec2-user/Dockerfile.git .
### Run:
docker run -it --name git ranjitswain/git:1.0
