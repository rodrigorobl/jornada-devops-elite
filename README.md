# jornada-devops-elite


### Comando para acessar o Grafana

```
kubectl get secret --namespace default grafana -o jsonpath="{.data.admin-password}" | base64 --decode ; echo
```