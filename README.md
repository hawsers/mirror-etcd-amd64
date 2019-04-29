# sh commands

```sh

VERSION=${VERSION}

docker pull hawsers/etcd-amd64:${VERSION}
docker tag hawsers/etcd-amd64:${VERSION} k8s.gcr.io/etcd-amd64:${VERSION}
docker rmi hawsers/etcd-amd64:${VERSION}
```
