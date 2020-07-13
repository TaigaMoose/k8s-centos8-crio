# k8s-shell-scripts
Shell scripts for install Kubernetes

### Install Kubernetes with CRI-O runtime on CentOS 8 - `cd ./crio-centos8`

**Prerequisites:**
* I recommend at least one host with minimum 2 cores, 4 GB RAM, 25 GB HDD  
* Installed CentOS 8 (I recommend "Server" profile)

**Сustomization:**
Set version of CRI-O and Kubernetes in `k8s-crio-setup.sh` if you want to change from 1.18: variable `REQUIRED_VERSION`

**Install:**

    sudo chmod +x k8s-crio-setup.sh && sudo ./k8s-crio-setup.sh
