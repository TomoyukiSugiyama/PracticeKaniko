# PracticeKaniko

```bash
cd kaniko
kubectl create secret docker-registry regcred --docker-server=<your-registry-server> --docker-username=<your-name> --docker-password=<your-pword> --docker-email=<your-email>
kubectl create -f volume.yaml
kubectl create -f volume-claim.yaml
kubectl create -f pod.yaml 
```