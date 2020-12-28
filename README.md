# ckad
CKAD preparation  

1. Create a pod using yaml

```kubectl apply -f pod/pod-definition.yaml```

2. Extracting a running pods definition in a yaml file

``` kubectl get pod <pod-name> -o yaml > pod-definition.yaml```

3. Replication controller helps us run multiple instances of pod for high availability and load balancing.

   Replication controller! = Replica set (  Replication controller is an older terminology)




