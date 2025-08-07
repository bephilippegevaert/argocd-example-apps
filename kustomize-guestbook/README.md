
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/bephilippegevaert/argocd-example-apps
# cd into the cloned directory
git checkout f63e2afb9eff3927c566400a67cf99e1c5bab54b
kustomize build ./kustomize-guestbook
```