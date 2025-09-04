# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/bephilippegevaert/argocd-example-apps
# cd into the cloned directory
git checkout 8a12fcacdcb6e1488156cbd9c9c296c5e3e9adc8
kustomize build ./kustomize-guestbook
```
