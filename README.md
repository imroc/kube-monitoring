# kube-monitoring

This is a helm chart of kubernetes monitoring stack.

## Usage

``` bash
git clone --depth 1 https://github.com/imroc/kube-monitoring.git
cd kube-monitoring
kubectl create namespace monitoring
helm install monitoring -n monitoring kube-monitoring
```
