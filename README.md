# vzmini - Ansible template Requirement from Interview

# pre-requisites

1. Install the boto libraries.

2. Set the AWS CLI credentials.

This playbook will perform below tasks,

1. Create a new key pair.

2. Launch a new instance with provided specifications.

3. wait for the ssh connection to come up.

4. Finally, run the `ifconfig` command and display the output.