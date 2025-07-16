Cloud-Native Web Voting Application with Kubernetes
--------------------------------------------------------
A cloud-native web application that allows users to vote for their preferred programming language from six choices: C#, Python, JavaScript, Go, Java, and NodeJS.

Features

-Interactive Frontend: Built with React for a responsive user experience
-Scalable Backend: Go-powered API handling voting requests
-Persistent Data Storage: MongoDB with replica set configuration
-Cloud-Native Architecture: Designed for Kubernetes deployment
-High Availability: Components distributed across Kubernetes cluster

Technical Stack
 -Frontend
    Framework: React
    Language: JavaScript
-Backend
    Language: Go (Golang)
    Database: MongoDB (with replica set)

-Infrastructure
    Container Orchestration: Kubernetes
    Containerization: Docker

Kubernetes Resources
This application leverages various Kubernetes resources for deployment:

Resource Type	                 Purpose
-----------------------------------------------------------------------
Namespace                	 Isolated environments for components
Secret	                     Secure storage of sensitive information
Deployment	                 Manages application instances and scaling
Service	                     Enables access to application components
StatefulSet	                 Manages stateful components (MongoDB)
PersistentVolume	         Provides persistent storage
PersistentVolumeClaim	     Claims storage resources
-----------------------------------------------------------------------

Getting Started
 -Prerequisites
    Kubernetes cluster (minikube, EKS, AKS, GKE, etc.)
    kubectl configured to access your cluster
    Docker (for building container images)

-Deployment
    Clone this repository:
       command : git clone <github link>
                 git init
                 cd <file name>

 -Apply Kubernetes manifests:                
          command : use all yaml file using  Kubectl apply -f <yaml file name>
          
-----------------------------------------------------------------------------------------
 
 Learning Opportunities
     -This project provides hands-on experience with:
     -Containerization with Docker
     -Kubernetes orchestration
     -Microservices architecture
     -MongoDB replica sets
     -Kubernetes secrets management
     -Stateful application deployment
     -Persistent storage in Kubernetes

Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements.

         
