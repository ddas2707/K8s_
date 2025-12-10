`kubectl get pods` — List all pods in the current namespace.

`kubectl get pods -o wide` — List pods with detailed information (IP, node, etc.).

`kubectl get pods --namespace=nginx` — List pods inside the `nginx` namespace.

`kubectl get nodes` — List all nodes in the Kubernetes cluster.

`kubectl apply -f pods.yaml` — Create/update resources defined in `pods.yaml`.

`kubectl delete -f pods.yaml --namespace=nginx` — Delete resources from `pods.yaml` in the `nginx` namespace.
