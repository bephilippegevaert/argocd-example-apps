# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/bephilippegevaert/argocd-example-apps
# cd into the cloned directory
git checkout 9a4594af020734e084accf922d7ac3edd4dcd430
helm template . --name-template uat-helm-guestbook --include-crds
```
