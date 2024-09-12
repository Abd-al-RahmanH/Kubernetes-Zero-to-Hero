## Kubernetes with Kubectl: Key Features

### 1. **Pod Deployment on Minikube**
- Deployed **nginx** pods in a **Minikube** single-node cluster using Kubernetes command-line tool **kubectl**.

### 2. **Auto-Scaling and Self-Healing**
- Configured deployment files to automatically scale pods based on load and enable self-healing of containers.

### 3. **Service Configuration**
- Set up **Services** with:
  - **Cluster IP**: For internal communication within the cluster.
  - **NodePort**: To expose services on a specific port outside the cluster.
  - **Load Balancer**: Distributed traffic across multiple pods, making the service publicly accessible using labels.

### 4. **Monitoring with Kubeshark**
- Used **Kubeshark**, an observability tool, to monitor and track requests made to the service.

### 5. **Ingress Controller Configuration**
- Configured an **Ingress** controller to manage external access to services, directing traffic to **Cluster IP** services.
- Optimized cost by using a single IP or DNS (ideal for scenarios like an eCommerce website).

### 6. **ConfigMaps and Secrets**
- Configured **ConfigMaps** and **Secrets** as volumes, mounting them directly to the container file system for easy management of configuration data and sensitive information.

### 7. **Custom Resources and GitOps**
- Explored Kubernetes custom resources, like **Argo CD** and **GitOps**, to manage continuous deployment and integrate version control with Kubernetes clusters.

---
