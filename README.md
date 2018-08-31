# kubernetes-dashboard

github addr [https://github.com/kubernets/kubernetes-dashboard](https://github.com/kubernets/kubernetes-dashboard)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/kubernetes-dashboard/raw/master/get-kubernetes-dashboard-image.sh

## Arch and Version

- [**amd64** v1.10.0](https://hub.docker.com/r/kubernets/kubernetes-dashboard-amd64)

    > docker pull kubernets/kubernetes-dashboard-amd64:v1.10.0

    > docker tag kubernets/kubernetes-dashboard-amd64:v1.10.0 gcr.io/google-containers/kubernetes-dashboard-amd64:v1.10.0 

    > docker rmi kubernets/kubernetes-dashboard-amd64:v1.10.0
