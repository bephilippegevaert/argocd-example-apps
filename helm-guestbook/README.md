# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/bephilippegevaert/argocd-example-apps
# cd into the cloned directory
git checkout e8f5ea9c4b54933743f5dd518dcf51d6a2139635
helm template . --name-template uat-helm-guestbook --include-crds
```
