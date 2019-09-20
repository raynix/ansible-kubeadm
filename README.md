# ansible-kubeadm
Use ansible to provision kubeadm cluster

- do `ssh-copy-id pi@192.168.1.x` on every Pi
- copy `inventory/cluster.example` to `inventory/cluster`
- run `ansible-playbook -i inventory/cluster kubeadm.yaml`
- add `-vvv` for debugging
