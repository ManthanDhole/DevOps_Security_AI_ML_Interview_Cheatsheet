## Kubernetes Revision Notes

### Kubernetes Architecture

A Kubernetes Cluster consist of:
1. Master Node (Control Plane) <br>
   a. kube-api <br> 
   b. etcd <br> 
   c. kube-scheduler <br> 
   d. kube-controller <br> 
   e. cloud controller manager <br> 

2. Worker Node (Application Workloads) <br>
   a. kubelet <br>
   b. containerd (Container Runtime) <br>
   b. kube-proxy <br>


   ### Kubernetes Core Objects

   1. Pod
   2. Replica Set
   3. Deployment
   4. Namespace
   5. Services
   6. Stateful Set
   7. Daemon Set
   8. ConfigMaps
   9. Secrets
   10. Persistent Volumes
