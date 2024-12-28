# sdcore_eupf_charts

### install sdcore with eupf
```bash
helm install sdcore ./sdcore-helm-charts/ -n sdcore
helm install eupf ./eupf/ -n sdcore
```

### install ueransim
```bash
helm install ueransim ./ueransim-gnb/ -n sdcore
```
> **Charts:** helm pull oci://registry-1.docker.io/gradiant/ueransim-gnb --version 0.2.6

