`kubectl get pods` — List all pods in the current namespace.

`kubectl get pods -o wide` — List pods with detailed information (IP, node, etc.).

`kubectl get pods --namespace=nginx` — List pods inside the `nginx` namespace.

`kubectl get nodes` — List all nodes in the Kubernetes cluster.

`kubectl apply -f pods.yaml` — Create/update resources defined in `pods.yaml`.

`kubectl delete -f pods.yaml --namespace=nginx` — Delete resources from `pods.yaml` in the `nginx` namespace.

for Cron-jobs
kubectl apply -f cronjob.yaml
kubectl get cronjobs -n nginx
kubectl get pods -n nginx
kubectl logs pod/minute-backup-29424127-4hxrp -n nginx
kubectl delete -f cronjob.yaml


############################################################

kubectl port-forward -n ingress-nginx svc/ingress-nginx-controller 8080:80  ---> ingress port forward command

