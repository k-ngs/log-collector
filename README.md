# elasticsearch-kibana
dockerおよびkubernetes上にElasticSearchとkibanaをデプロイする。

## docker-compose
コンテナ立ち上げ
```
$ cd elasticsearch-kibana
$ docker-compose up
```

## Kubernetes
kubernetesへデプロイ
```
$ helm install elasticsearch-kibana/log-collector
```

