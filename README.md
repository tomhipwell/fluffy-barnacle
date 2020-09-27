# fluffy-barnacle

A simple kubernetes deployment of a container running Debian. Useful when spinning up new clusters to probe the network from within or as a temporary  launchpad to explore a cluster when in development mode. Don't use in prod and always delete the deployment once you're done using it. Assuming you have the right permissions and your context set correctly then you can deploy with:

```bash
kubectl config apply -f ./deployment.yaml
```
