# fluent

Add fluent helm repo:
```bash
helm repo add fluent https://fluent.github.io/helm-charts
```

Install fluent-bit:
```bash
helm upgrade -i fluent-bit fluent/fluent-bit \
  -n logging \
  --create-namespace \
  -f values.yaml
```

