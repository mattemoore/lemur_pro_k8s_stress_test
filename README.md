# Stress testing my new System76 Lemur Pro ultralightweight laptop with 40GB RAM runninng Pop OS :)
1. Install docker `sudo apt install docker.io`
2. Install kubectl https://kubernetes.io/docs/tasks/tools/install-kubectl/#install-kubectl-on-linux
3. Install minikube https://minikube.sigs.k8s.io/docs/start/
4. `minikube start --driver=docker`
5. `kubectl apply -f manifest.yaml`
6. `kubectl get pods`
7.  `free`

