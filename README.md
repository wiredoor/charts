# Wiredoor Charts

You can find available helm charts provided by [Wiredoor](https://www.wiredoor.net), ready to lauch on Kubernetes using [Helm](https://github.com/helm/helm).

## Usage

```bash
helm repo add wiredoor https://charts.wiredoor.net
helm search repo wiredoor
helm install my-wiredoor-release wiredoor/wiredoor-gateway --set wiredoor.server=https://my-wiredoor.example.com --set wiredoor.token=secret_access_token 
```
