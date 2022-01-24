# k8s
My collection of Kubernetes resources

## regcred
Pull images from a private registry requires registry credentials saved in the namespace. Note, you'll need to remove the existing `regcred` secret if one already exists. Also, `regcred` is just a common naming convention... name it whatever you want.

```
kubectl -n [namespace] create secret docker-registry regcred --docker-server=[server] --docker-username=[username] --docker-password=[password]
```
