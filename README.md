# Learning-Docker-and-K8s
Contains code to deploy PODs, Services and Deployments using kubernetes and docker. 

<h2>Running a POD</h2>
<ul>
  <li>1.  kubectl apply -f Deployment/pod.yml </li>
  <li>2. kubectl port-forward my-api1 8081:5000 (When PODs are created, they are assigned a cluster IP. So we need to forward the port using this command) </li>
</ul>
<h2>Deployment Commands</h2>
Commands:
<ul>
  <li>1. kubectl get deployment --show-labels</li>
  <li>2. kubectl apply -f [filepath]</li>
  <li>3. kubectl delete deployment [name]</li>
  <li>4. kubectl scale deployment [name] --replica-set=5</li>
</ul>



