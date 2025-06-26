# Kubernetes with Azure AKS - Learning Repository

This repository contains the complete implementation and documentation of my **Week 6 assignment** given during my **2-month internship at Celebal Technologies**. The assignment focuses on hands-on Kubernetes and Azure Kubernetes Service (AKS) concepts, helping me explore workload management, service types, storage, probes, scaling, and more.

## 🎯 Assignment Tasks
This assignment covers:
- Deploying ReplicaSets, Replication Controllers & Deployments
- Kubernetes Service Types: ClusterIP, NodePort, LoadBalancer
- PersistentVolume (PV) and PersistentVolumeClaim (PVC)
- Managing Kubernetes with Azure Kubernetes Service (AKS)
- Scaling and upgrading AKS clusters
- Configuring Liveness and Readiness probes
- Implementing Taints and Tolerations
- Creating and attaching PersistentVolumeClaims to Pods
- Configuring Health Probes
- Autoscaling with Horizontal Pod Autoscaler (HPA)

## 🎥 Resources
This project also references videos and official documentation:
- [Kubernetes Controllers & Deployments](https://youtu.be/iAxBaTMoRwo), [Video 2](https://www.youtube.com/watch?v=mEnCFazQ8BM)
- [Service Types Overview](https://www.youtube.com/watch?v=T4Z7visMM4E)
- [PV/PVC Concepts](https://youtu.be/0swOh5C3OVM)
- [Managing AKS & Scaling](https://learn.microsoft.com/en-us/azure/aks/)
- …and more (see the full assignment for links)

## 🖼️ Screenshot Preview
Here’s a preview of the deployed app interface:
![Project Screenshot](screenshot.png)

## 📝 How to Run Locally
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
   ```
2. Navigate into the project directory:
   ```bash
   cd your-repo-name
   ```
3. Review the YAML files under k8s/ for deployments, services, and scaling configurations.
4. Deploy to your Kubernetes cluster using kubectl:
   ```bash
   kubectl apply -f k8s/
   ```
5. See the outputs with:
   ```bash
   kubectl get all
   ```
---
## 🤝 Contributions
Feel free to fork this repository and submit pull requests for improvements or bug fixes.

---
## 📄 License
This project is licensed under the MIT License.
