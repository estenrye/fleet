```bash
helm uninstall -n cattle-monitoring-system rancher-monitoring
helm uninstall -n cattle-monitoring-system rancher-monitoring-crd
kubectl delete namespace cattle-monitoring-system
kubectl delete namespace cattle-dashboards
```