ansible-petclinic
==================
- Install pip : sudo apt-get install python-pip
- Install ansible : sudo pip install ansible
- Launch playbook : ansible-playbook petclinc.yml -i hosts

For Ubuntu instances:

chmod 600 ec2-keypair.pem
ssh -v -i ec2-keypair.pem ubuntu@ec2-54-69-162-11.us-west-2.compute.amazonaws.com
