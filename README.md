== Introduction ==

This is a Kubernetes / Minikube example, how to create a simple, working Wordpress (+ MySQL) application. 

Based on the official Kubernetes documentation: https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/

== Install ==

1. Download the yaml file:

	$ wget https://github.com/ggferenczi/kubernetes/blob/master/wordpress.yaml

2. Or clone the git repo:

	$ git clone https://github.com/ggferenczi/kubernetes.git

== Running ==

If you already have an installed environment, for eg. Minikube os Kubernetes cluster, you can run the application:

	$ kubectl create -f wordpress.yaml

== Check ==


If you are using Minikube, than you can watch your created app with a one-line-command:

	$ minikube service wordpress


