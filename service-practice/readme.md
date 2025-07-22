kubectl create deployment nginx --image=nginx --dry-run=client  -o yaml > nginx-deployment.yaml
kubectl create ns  nginx-ns  --dry-run=client  -o yaml > nginx-ns.yaml  
kubectl create service clusterip deployment-lebel --tcp=80:80 --dry-run=client -o yaml > nginx-service.yaml


