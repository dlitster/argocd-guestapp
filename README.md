# argocd-guestapp

The GitOps "desired state" repo for the `k8s-control-loops-workshop`'s
git-driven-sync exercise (exercise 04).

Argo CD's `guestbook-git` Application watches this repo. Edit
`deployment.yaml` (e.g. change `replicas`), commit, and push — Argo CD
reconciles the cluster to match within its poll/webhook interval.

Originally copied from `manifests/guestbook/` in
[k8s-control-loops-workshop](https://github.com/dlitster/argocd-workshop).
