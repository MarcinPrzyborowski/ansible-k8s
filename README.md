# Ansible k8s for ubuntu 18.04

## Quick start

1. `ansible-playbook -i hosts ~/kube-cluster/initial.yml`
2. `ansible-playbook -i hosts ~/kube-cluster/kube-dependencies.yml`
3. `ansible-playbook -i hosts ~/kube-cluster/master.yml`
4. `ansible-playbook -i hosts ~/kube-cluster/workers.yml`
