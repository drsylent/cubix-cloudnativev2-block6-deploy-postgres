# Cubix Cloud-Native Application Development Training: cloud-native requirements (PostgreSQL deployment)
Fork this repository for the practice session.

## How to start the Chart

Replace password setting.

```shell
helm upgrade postgresql bitnami/postgresql --version 14.3.3 -n cubix -f values.yaml --install --set auth.password=<ENTER-PASSWORD>
```
