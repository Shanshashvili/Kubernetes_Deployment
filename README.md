# Kubernetes Deployment

## Task:
-	Create a YAML file to deploy a nginx application in Kubernetes.
-	Include a Deployment with 2 replicas and a Service to expose the application on port 80.
-	Apply the configuration using kubectl and verify the pods are running.

## Steps:

### **1. Clone GitHub Repository to the Kubernetes Cluster Machine**

### **2. Navigate into the Cloned Repository**
note: Make sure your `nginx-deployment.yaml` file is inside this directory.

### **3. Apply the Configuration to Kubernetes**
```bash
kubectl apply -f nginx-deployment.yaml
```
note: This will deploy the NGINX application defined in your YAML file to Kubernetes.

### **4. Check the Status of Your Deployment**

```bash
kubectl get pods
```

note: You should see the NGINX pods listed here, along with their status.
