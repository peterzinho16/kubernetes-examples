# Installation in docker desktop
### Resume
Modify the args in the deployment inside the file components.yaml
### Change

```
args:
  - --cert-dir=/tmp
  - --secure-port=4443
  - --kubelet-insecure-tls
```

### Source

https://github.com/kubernetes-sigs/metrics-server
https://blog.codewithdan.com/enabling-metrics-server-for-kubernetes-on-docker-desktop/
