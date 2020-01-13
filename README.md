# node-red
node-red kubed, tested on AKS

If you don't have created the StorageClass to use azure-files, execute the following command.

```
kubectl apply -f dependencies
```

Install using
```
kubectl apply -f k8s
```

You can see the custom docker image [here](https://github.com/isma90/node-red-1)
