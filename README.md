## Helm chart for Envoy-Pilot

[Envoy-Pilot](https://github.com/tak2siva/Envoy-Pilot) is a simple xDS Server or control plane implementation for Envoy.

Usage:

```
helm install ../Envoy-Pilot-Helm --namespace envoy-pilot --name envoy-pilot --set config.CONSUL_PATH="http://consul-consul.default:8500"
```
