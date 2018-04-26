# kubernetes-yaml-examples

**Useful commands:**

>kubectl get  # list resources

>kubectl describe  # resource details

>kubectl explain

>kubectl get componentstatuses  # cluster component health

>kubectl get pv --sort-by="spec.capacity.storage"  # list persistent volumes by capacity

>kubectl run -i --tty busybox --image=busybox -- sh  # busybox interactive shell

>kubectl run curl --image=radial/busyboxplus:curl -i --tty # interactive shell with curl
