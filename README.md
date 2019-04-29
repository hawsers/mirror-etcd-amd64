# sh commands

```sh

VERSION=${VERSION}

docker pull hawsers/etcd-amd64:${VERSION}
docker tag hawsers/etcd-amd64:${VERSION} gcr.io/google_containers/etcd-amd64:${VERSION}
docker rmi hawsers/etcd-amd64:${VERSION}
```
