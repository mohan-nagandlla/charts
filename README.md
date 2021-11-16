# charts

You can add this helm repo by helm command 
```
helm repo add observablity https://mohan-nagandlla.github.io/charts/
helm repo update
```

you can able to get the packages by search command 

```
helm search repo observablity
```

If you found any desired package then the installing command is 

```
helm show values observablity/[chart name] > valeus.yaml
helm install [release name] observablity/[chart name] -n [namespace] -f values.yaml
```
