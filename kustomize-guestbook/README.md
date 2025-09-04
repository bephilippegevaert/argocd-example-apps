# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/bephilippegevaert/argocd-example-apps
# cd into the cloned directory
git checkout 51455a00213eec2962a3e287c75f100c70ed4195
kustomize build ./kustomize-guestbook
```
