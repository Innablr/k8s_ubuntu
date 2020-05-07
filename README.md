# k8s_ubuntu

Quickly set up a Kubernetes cluster on virtualbox

1.	`git clone https://github.com/Innablr/k8s_ubuntu.git`
2.	`cd k8s_ubuntu`
3.	`cp bootstrap_kmaster_flannel.sh bootstrap_kmaster.sh # optional to use flanel`
4.	`vagrant up`
5.	`vagrant ssh kmaster -c 'kubectl get nodes -o wide'

See https://blog.exxactcorp.com/building-a-kubernetes-cluster-using-vagrant/
Forked from https://exxsyseng@bitbucket.org/exxsyseng/k8s_ubuntu.git

Limitations: load-balancers don't get external IPs
