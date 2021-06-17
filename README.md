# promoes-kong-postgres

## Setup
1. Create `kong` namespace
```
kubectl create namespace kong
```
2. Deploy postgres.yaml
```
kubectl apply -f postgres.yaml
```
3. Deploy migration.yaml

4. Deploy kong.yaml
