## Magento ansible playbook
Ansible playbook for Magento and deps installation on cloud images - AWS EC2 AMI Linux Cloud Server and GCP CentOS/RHEL 7. Tested on Lightsail service but it can work in any EC2 AWS AMI Linux image. Tested also on Google Cloud Platform.

## Instructions
Edit hosts file with proper parameters and run the following command:
`ansible-playbook -i hosts playbooks/install.yml`