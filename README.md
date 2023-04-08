# msvc-kubernetes-aws
msvc-kubernetes-aws

The intention of the project is to address a use with kubernetes.
4 microservices are used in didactive mode, to carry out the deployment in minikube and AWS-EKS. 
Docker-Kubernetes-FeingClient-SpringCloudKubernetes


4 microservices were used 

![](images/msvc.gif)

The microservices have two separate databases, and they communicate with each other by FeingClient.

![](images/feingClient.gif)

The persistent volume was used to save the data from the databases.

![](images/pv.gif)

Spring Cloud Kubernetes was used to communicate with Kubernetes from Spring.

![](images/springCloud.gif)

Demo Deploy Minikube
[![Deploy Minikube](images/deploy-minikube.gif)](https://www.youtube.com/watch?v=-uNC5yHD04Y)


Demo Deploy aws-eks
[![Deploy Aws](images/deploy-aws.gif)](https://www.youtube.com/watch?v=gFxH9_qi6bU)