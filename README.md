Here's Ansible playbook for a static website using HTML which created on EC2 AWS instances which you can run in redhat or ubuntu nodes.


Kindly Note that:


In ansible.cfg file  ---> the line of remote user is ansible so please makesure to add it on nodes before running the playbook or remove it in the first run of the playbook because this task is already added in the playbook.

So after first run, you'll have ansible user which also added to sudoers file.
