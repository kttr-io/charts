# CSI snapshot-controller

This chart installs the CSI snapshot-controller and its CRDs.

> This chart installs components in the `kube-system` namespace.
> Take care not to install multiple instances of the chart (or other instances of `snapshot-controller` not managed by this chart).

## Installation
```
helm repo add kttr-io https://charts.kttr.io
helm repo update
helm install my-release kttr-io/csi-snapshot-controller
```