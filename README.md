![img.png](img.png)
- helm install -f values/<<values-file>> <<relaeseName>> microservice
- helm template -f values/redis-values.yaml charts/redis

### using helmfile
- helmfile sync
- helmfile destroy
