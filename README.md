# my-k8s-operator

```
$ kubebuilder init --domain dev.montree.me --repo=github.com/gailo22/my-k8s-operator
$ kubebuilder create api --group example --version v1alpha1 --kind Example

$ minikue start

$ make install
$ make run

$ k get crds -A
NAME                              CREATED AT
examples.example.dev.montree.me   2023-09-18T03:05:25Z
```


## reference
- https://go.dev/doc/manage-install#installing-multiple
- 