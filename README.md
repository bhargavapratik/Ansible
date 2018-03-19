# Ansible
Ansible Assignmets on AWS
# Deploy VPC with One Private and two Public Subnets 
# Create EC2 Instance,
# Create Aplication Load Balancer
# Create DNS in Route53
# Install Httpd (Apache2), Docker and Grafana and Graphite
# Add EC2 Instace to ALB and Update ALB DNS in Route 53.
To run this playbook.

    clone the repo
    
    export ANSIBLE_HOST_KEY_CHECKING=False
   
    update varibles values in group_vars/all

    run ansible-playbook -i hosts  aws_playbook.yml  --private-key YOUR-EC2-PRIVATEKEY.pem

