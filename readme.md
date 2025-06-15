# k8-workstation

- Create infra

- login to superputty 

- sudo su -

- git clone https://github.com/eswar-sai-kumar/k8-eksctl.git

- cd k8-eksctl

- sh workstation.sh

- aws configure

- eksctl create cluster --config-file=eks.yaml (usually takes 15 minutes)

- kubectl get nodes 

- kubectl version

- eksctl delete cluster --config-file=eks.yaml