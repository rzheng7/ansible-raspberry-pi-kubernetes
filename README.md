# ansible-raspberry-pi-kubernetes
Ansible playbooks for building a Raspberry Pi Kubernetes Cluster

Reference: https://aporcupine.com/2020/03/pi4-kubernetes-cluster/

```
sudo sed -i '$ s/$/ cgroup_enable=cpuset cgroup_enable=memory cgroup_memory=1 swapaccount=1/' /boot/firmware/cmdline.txt
```
