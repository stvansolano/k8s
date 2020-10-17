  cd istio && mkdir install && cd install
  curl -L https://istio.io/downloadIstio | sh -
  chmod +x istio-1.7.3/bin/istioctl && sudo mv istio-1.7.3/bin/istioctl /usr/local/bin/istioctl
  istioctl install --set profile=demo

## Getting started
- https://istio.io/latest/docs/setup/getting-started/