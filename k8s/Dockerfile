FROM k8s.gcr.io/kube-apiserver:v1.12.0
FROM k8s.gcr.io/kube-controller-manager:v1.12.0
FROM k8s.gcr.io/kube-scheduler:v1.12.0
FROM k8s.gcr.io/kube-proxy:v1.12.0
FROM k8s.gcr.io/pause:3.1
FROM k8s.gcr.io/etcd:3.2.24
FROM k8s.gcr.io/coredns:1.2.2
MAINTAINER wwhui@tepusoft.com


docker pull  docker.io/wwhui/kube-apiserver:v1.12.0
docker pull  docker.io/wwhui/kube-controller-manager:v1.12.0
docker pull  docker.io/wwhui/kube-scheduler:v1.12.0
docker pull  docker.io/wwhui/kube-proxy:v1.12.0
docker pull  docker.io/wwhui/pause:3.1
docker pull  docker.io/wwhui/etcd:3.2.24
docker pull  docker.io/wwhui/coredns:1.2.2

docker tag  docker.io/wwhui/kube-apiserver:v1.12.0    k8s.gcr.io/kube-apiserver:v1.12.0
docker tag  docker.io/wwhui/kube-controller-manager:v1.12.0    k8s.gcr.io/kube-controller-manager:v1.12.0
docker tag  docker.io/wwhui/kube-scheduler:v1.12.0    k8s.gcr.io/kube-scheduler:v1.12.0
docker tag  docker.io/wwhui/kube-proxy:v1.12.0    k8s.gcr.io/kube-proxy:v1.12.0
docker tag  docker.io/wwhui/pause:3.1   k8s.gcr.io/kube-proxy:pause:3.1
docker tag  docker.io/wwhui/etcd:3.2.24  k8s.gcr.io/etcd:3.2.24
docker tag  docker.io/wwhui/coredns:1.2.2 k8s.gcr.io/coredns:1.2.2