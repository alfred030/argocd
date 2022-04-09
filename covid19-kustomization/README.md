
## Install kustomize
```
curl -s "https://raw.githubusercontent.com/kubernetes-sigs/kustomize/master/hack/install_kustomize.sh" | bash
install -o root -g root -m 0755 kustomize /usr/local/bin/kustomize
```
## Apply kustomize in the cluster
kustomize build ./ | kubectl apply -f -