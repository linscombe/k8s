# Kubernetes - WordPress and MySQL with Persistent Volumes
based on the origional tutorial from kubernetes.io

https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/


## Apply kustomization
Run the following command to create the Secret, Deployments, Services and PersistentVolumeClaims:
```
kubectl apply -k ./
```

## Clean up
Run the following command to delete the Secret, Deployments, Services and PersistentVolumeClaims:
```
kubectl delete -k ./
```
