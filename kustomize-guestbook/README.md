
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/bephilippegevaert/argocd-example-apps
# cd into the cloned directory
git checkout c461d064a381f2bed350ed2ace4dafac48057c89
kustomize build ./kustomize-guestbook
```