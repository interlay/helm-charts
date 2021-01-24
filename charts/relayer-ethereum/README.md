# Helm Charts

[stable/bitcoind](https://github.com/helm/charts/tree/master/stable/bitcoind)

```bash
# to pull docker image
kubectl create secret docker-registry regcred --docker-server=registry.gitlab.com --docker-username=<token> --docker-password=<token>

# to submit transactions
kubectl create secret generic ethereum --from-literal privateKey=<hex> --from-literal url=<infura> --from-literal address=<hex>
```