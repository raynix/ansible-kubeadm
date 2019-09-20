# ansible-kubeadm
Use ansible to provision kubeadm cluster

1, do `ssh-copy-id pi@192.168.1.x` on every Pi
2, copy `inventory/cluster.example` to `inventory/cluster`
3, run `ansible-playbook -i inventory/cluster kubeadm.yaml`
4, add `-vvv` for debugging
