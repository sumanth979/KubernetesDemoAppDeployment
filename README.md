# KubernetesDemoAppDeployment
Sample Voting App deployment in a micro services architecture.

#### The Deployment Invloves the following Steps:

##### Step-1: Pre Requsites:
* The Machine should be installed
  * Minikube
  * Oracle VirtualBox
  * Kubectl

* This deployment will make use of exisiting images in Docker Hub

##### Step-2: Creating Deployment Files:
* Create the appropriate deployment Files

##### Step-3: Creating Service Files:
* Create the appropriate service Files

##### Step-4: Deploy the app
* Deploying Application
```bash
kubectl create -f *.yaml
```
* Get the Service url
```bash
minikube service serviceName --url
```
* Use the service URL of Voting App and Result App to validate the Application deployment.

