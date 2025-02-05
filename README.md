## Apply kustomize to NNCP & NAD

This repo contains an example of applying a kustomize overlay to patch a set of
NNCPs and NADs for configuring secondary (Multus) networks in
Kubernetes/OpenShift.

The idea is to replace the IP addresses and interface names in the overlay.

To render, install kustomize and run `kustomize build ./overlays/bond1-worker02`
