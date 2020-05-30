# Stress testing my new System76 Lemur Pro ultralightweight laptop with 40GB RAM running Pop OS :)
1. Install docker `sudo apt install docker.io`
2. Install kubectl https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-kubectl-on-linux
3. Install minikube https://minikube.sigs.k8s.io/docs/start/
4. `minikube start --driver=docker`
5. `kubectl apply -f manifest.yaml`
6. `kubectl get pods`
7.  `free`

Notes/Questions
# 10GB RAM assigned to minikube container
# Only 3GB change to free/available RAM?