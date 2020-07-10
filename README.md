# k8s-centos8-crio
Bash script for install Kubernetes with CRI-O to CentOS 8 
 
### Prerequisites: 
1. Host with minimum 2 cores, 4 GB RAM, 25 GB HDD  
2. Installed CentOS 8 (I reccomend "Server" profile) 
 
### Install 

    git clone https://github.com/TaigaMoose/k8s-centos8-crio 
    cd k8s-centos8-crio
    
#### Set version of CRI-O and Kubernetes in k8s-crio-setup.sh if you to change from 1.18: variable REQUIRED_VERSION 
#### Then install CRI-O and Kubernetes  
    
    chmod +x k8s-crio-setup.sh
    sudo ./k8s-crio-setup.sh
