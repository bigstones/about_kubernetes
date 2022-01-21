# about_kubernetes

## 쿠버네티스 학습 경로

[쿠버네티스 기초 학습](https://kubernetes.io/ko/docs/tutorials/kubernetes-basics/)


[따라하면서 배우는 쿠버네티스](https://www.youtube.com/playlist?list=PLApuRlvrZKohaBHvXAOhUD-RxD0uQ3z0c)

## 쿠버네티스 IDE

[play with k8s](https://labs.play-with-k8s.com/)

[kubernetes playground](https://www.katacoda.com/courses/kubernetes/playground)


## 명령어

kubeadm : the command to bootstrap the cluster.

kubelet : the component that runs on all of the machines in your cluster and does things like starting pods and containers.

kubectl : the command line util to talk to your cluster.

## kube 명령어 실행

    $ mkdir -p $HOME/.kube
    $ sudo cp -i /etc/kubernetes/admin.conf $HOME/.kube/config
    $ sudo chown $(id -u):$(id -g) $HOME/.kube/config
