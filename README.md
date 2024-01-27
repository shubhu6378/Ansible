# Ansible
All Anisble practice repo-----------


# As before using ansible few prerequisites needs to be performed :
Launch atleast 2 EC2 instance.
login to EC2 instance-
.sudo apt update  <For updating all packages and version in server>
.sudo apt install ansible <For installing Ansible>

Once Ansible is installed.
We have to enable paswordless communication between master server to slave server.
As Anisbile works on push mechanism so we needs to enable paswordless communication show that we can ssh from master server to slave server.

Steps for enabling paswordless communication:
ssh-keygen < this is create a public key,private key and authorized key>
run above command in both server.
post creation of key we have to copy the public key of master server to slave server under authorized key.

post that paswordless communtication will be establisted.
