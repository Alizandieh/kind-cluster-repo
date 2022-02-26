# Configuration repo for a Kind cluster

---------------------------------------

Flux bootstrap command:

```
export GITHUB_TOKEN=<your-token>

flux bootstrap github \
  --owner=Alizandieh \
  --repository=kind-cluster-repo \
  --branch=master \
  --path=/ \
  --personal \
  --components-extra=image-reflector-controller,image-automation-controller 

```