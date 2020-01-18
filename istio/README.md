# Istio

## Generate K8s manifests with Istioctl - version 1.4.3
```baseh
istioctl manifest generate --set profile=demo --set values.gateways.istio-ingressgateway.sds.enabled=true > istio/istio.yaml
```