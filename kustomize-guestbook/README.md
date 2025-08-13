
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/bephilippegevaert/argocd-example-apps
# cd into the cloned directory
git checkout 75463ec8ed4582ffbf0031afe448f8d554cb8743
kustomize build ./kustomize-guestbook
```