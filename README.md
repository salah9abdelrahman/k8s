# Commands
- To start minikube `minikube start`
- Explore the dashboard `minikube dashboard`
- Create a pod defined in yml file `kubectl create -f db.yml`
- Get pods `kubectl get pods` or for more info `kubectl get pods -o wide`. To parse the output as json `kubectl get pods -o json` or yml `kubectl get pods -o yaml`
- The describe sub-command returned details of the specified resource `kubectl describe pod db`
- delete pod `kubectl delete -f db.yml`
