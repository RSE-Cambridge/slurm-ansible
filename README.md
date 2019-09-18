# slurm-ansible

Ansible role to install Slurm on RedHat-based distributions.

Clone this repo into your roles directory.

Example inventory file:

```
[slurm:children]
slurm_master
slurm_workers

[slurm_master]
your_slurm_master

[slurm_workers]
your_compute_node1
your_compute_node2
```
