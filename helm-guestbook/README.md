
# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell

git clone https://github.com/bephilippegevaert/argocd-example-apps
# cd into the cloned directory
git checkout fc32553d25cc9a42f1c3b4dbb9146e2f9a934a9d
helm template . --name-template dev-helm-guestbook --include-crds
```