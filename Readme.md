# Please follow below steps to set up the Ansible instance
# 1. Installation for Ansible:
Steps:
- Launch EC2 instance
- Access the EC2 instance Putty or MobaXtreme
- Please execute below commands:
    sudo yum install python
    sudo yum install python-pip
    sudo amazon-linux-extras install ansible2 -y
    sudo pip install boto3
- After the installation check the versions whether all the softwares installed properly or not
- Created ec2_instance.yaml file for creating EC2 instance with Security group with restricted ports open.
- ansible-playbook ec2_instance.yaml #(execute this command to verify ec2 instance or debug the issues)

