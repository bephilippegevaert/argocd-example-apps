# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/bephilippegevaert/argocd-example-apps
# cd into the cloned directory
git checkout 2d34b111aa8e2533005e74b9f251769a273c2060
kustomize build ./kustomize-guestbook
```
