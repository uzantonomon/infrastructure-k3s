# infrastructure-k3s
- Install cert-manager

kubectl apply -f https://github.com/cert-manager/cert-manager/releases/latest/download/cert-manager.yaml

- Get a shell on a pod

kubectl exec -n <namespace-name> -it <pod-name> -- sh
