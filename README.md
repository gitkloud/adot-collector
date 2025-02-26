# adot-collector

1. Change the values in values.yaml
    Add the aws creds

2. Create a namespace `otel` if not present
```
helm upgrade --install adot-collector . -n otel --create-namespace
```
