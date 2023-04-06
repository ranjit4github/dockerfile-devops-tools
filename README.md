# Dockerfile of All DevOps tools
# Ansible
## How to use it?
### Build:
docker build -t ranjitswain/ansible:1.0 -f /home/ec2-user/Dockerfile.ansible .
### Run:
docker run -it --rm --name mbansible ranjitswain/ansible:1.0
