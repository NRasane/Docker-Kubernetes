# Docker-Kubernetes
Ansible playbooks to get ready with Docker CE installation and Kubernetes with pod network configuration
Added yml scripts


steps to setup ansible (install Ansible on localhost)

1> localhost where we can able to create ssh-key to share on master for primary connectivity

2> having 1 master and 2 worker nodes on AWS (port opened 80,443,22)

3> step 1 to follow from master to worker nodes

4> create one folder ie. mkdir ~/dk-cluster on localhost

5> add hosts file which will read all servers IP and hostnames

6> create docker.yml and run it

7> create initial.yml, kube-dependencies.yml, master.yml and workers.yml and run in same sequence

eg: ansible-playbook -i hosts ~/dk-cluster/<playbook_name>.yml (from localhost where ansible is installed)
