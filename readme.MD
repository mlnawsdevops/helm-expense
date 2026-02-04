# helm 

### file structure
1. Chart.yaml
2. values.yaml
3. templates
    1. deployment.yaml
    2. service.yaml
    3. manifest.yaml

### helm installation
Ref: https://helm.sh/docs/intro/install/
```
curl -fsSL -o get_helm.sh https://raw.githubusercontent.com/helm/helm/main/scripts/get-helm-4
chmod 700 get_helm.sh
./get_helm.sh
```

### helm commands
```
1. helm intall <chart-name> .
2. helm list
3. helm env
4. helm uninstall <chart-name> .
5. unset HELM_NAMESPACE
6. helm list -A
7. helm upgrade <chartname> . -n default
8. helm history <chartname> -n default
9. helm rollback <chartname> 1
10. helm rollback <chartname>
11. helm uninstall <chartname> -n <namespacce>
12. helm repo add <url>
13. helm repo update
14. helm upgrade --install 
15. helm list -n kube-system
```