# fleet-cert-manager
Fleet gitrepo for cert-manager

#### Install Fleet via Helm

```
$ helm repo add fleet https://rancher.github.io/fleet-helm-charts/
$ helm -n fleet-system install --create-namespace --wait fleet-crd fleet/fleet-crd
$ helm -n fleet-system install fleet fleet/fleet
```
