# weavenet-rmpeers

Hacky fix for [this bug on weave](https://github.com/weaveworks/weave/issues/2797) which
eventually can make the cluster not launch new pods.

```console
kubectl create -f https://raw.githubusercontent.com/caarlos0/weavenet-rmpeers/master/weave-net-rmpeers.yaml
```
