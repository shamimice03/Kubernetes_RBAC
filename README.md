# Give user and groups access to kubernetes cluster

## Generate kubeconfig for a user using the script
### Download the script
```
curl https://raw.githubusercontent.com/shamimice03/Kubernetes_RBAC/main/generate-kubeconfig.sh > generate_kubeconfig.sh
```

### Make the file executable
```
chmod +x generate_kubeconfig.sh
```
### Execture the script, terminal will ask for the Username,Group Name and Namespace Name. Finally, type "yes" for execution.
```
bash generate_kubeconfig.sh
```


