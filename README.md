# configure-multi-node-kubernetes-cluster-using-ansible
Description of the Ansible Galaxy  roles.

Master role: Configure the master host and generate token so slave can get connected.
 - Command: ansible-galaxy install harneetsingh11.configure_kubernetes_cluster_master_node

Slave role: Congigure the slave hosts , need master token to connect to master
 - Command: ansible-galaxy install harneetsingh11.configure_kubernetes_cluster_worker_node


