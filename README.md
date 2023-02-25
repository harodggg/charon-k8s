# charon-k8s

## 1, Deploy k8s/k3s in different public network environments

- [kubeshpere](https://kubesphere.io/en)
- [k3s](https://k3s.io/)
- [wireguard](https://www.wireguard.com/)
- [k8s](https://kubernetes.io/)
  
## 2，Install the gcp csi plugin to implement dynamic volumes
[csi-gcs](https://ofek.dev/csi-gcs/dynamic_provisioning/)

## 3，One-click deployment of Ethereum consensus layer and execution layer on gcp

```bash
kubectl apply -k nethermind-lighthouse-storage-bucket
```

## 4, Install the cluster key

```bash
docker run --rm -v "$(pwd):/opt/charon" obolnetwork/charon:v0.13.0 create cluster --withdrawal-address="0x0257Cd0453243D228482f93F58b17adEA4F532B1" --nodes 4 --threshold 3 --name g-xbt
```