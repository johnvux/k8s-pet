Bootstrap the app:
```bash
docker build . -t k8s-pet
kubectl apply -f .\k8s-objects
```