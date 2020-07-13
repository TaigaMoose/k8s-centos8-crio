# k8s-shell-scripts
Shell scripts for setup Kubernetes


### Install Kubernetes with CRI-O runtime on CentOS 8 - `cd ./crio-centos8`

**Prerequisites:**
* I recommend at least one host with minimum 2 cores, 4 GB RAM, 25 GB HDD  
* Installed CentOS 8 (I recommend "Server" profile)

**Install:**  
Set version of CRI-O and Kubernetes:

    export REQUIRED_VERSION=1.18

Execute script:

    sudo chmod +x k8s-crio-setup.sh && sudo ./k8s-crio-setup.sh
