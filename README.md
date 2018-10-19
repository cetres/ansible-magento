## Magento on AWS Linux AMI
Ansible playbook for Magento and deps installation on AWS EC2 AMI Linux Cloud Server. Tested on Lightsail service but it can work in any AWS AMI Linux image

## Instructions
Edit hosts file with proper parameters and run the following command:
`ansible-playbook -i hosts magento.yml`