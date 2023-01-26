# Kubernetes
Understanding Kubernetes
Documentation Reference: https://kubernetes.io/docs/home/

###### kubectl commands
      kubectl get nodes
      kubectl get pod
      kubectl get services
      kubectl get deployment
      kubectl get replicaset

###### debugging
     kubectl logs {pod-name}
     kubectl exec -it {pod-name} -- bin/bash
     kubectl describe pod {pod-name}

###### delete deplyoment
     kubectl delete deployment {pod name}
     kubectl delete activity {podname}

###### create or edit config file
     nano nginx-pod.yaml
     kubectl apply -f nginx-pod.yaml

###### delete with config
     kubectl delete -f nginx-pod.yaml
