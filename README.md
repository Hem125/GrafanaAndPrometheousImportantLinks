# GrafanaAndPrometheousImportantLinks

Link for Grafana And Prometheous

https://computingforgeeks.com/setup-prometheus-and-grafana-on-kubernetes/

to get grafana password:

kubectl get secret --namespace monitoring grafana -o jsonpath="{.data.admin-password}" | base64 --decode ; echo
