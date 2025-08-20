# Manifest Hydration

To hydrate the manifests in this repository, run the following commands:

```shell
git clone https://github.com/bephilippegevaert/argocd-example-apps
# cd into the cloned directory
git checkout fc2d027b6e72e94acc7eec26e4b017fcb0da1527
helm template . --name-template tst-helm-guestbook --include-crds
```
