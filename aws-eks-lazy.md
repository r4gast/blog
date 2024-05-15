# AWS-EKS Essentials & Logging & Threat Detection

## Terms

Kubernetes | 
AWS EKS |
Cluster |
Node| 
Pode |
App |



## Logging Options -> AWS EKS Control Plane Logging

### API server (api) 
Your cluster's API server is the control plane component that exposes the Kubernetes API. If you enable API server logs when you launch the cluster, or shortly thereafter, the logs include API server flags that were used to start the API server. For more information, see kube-apiserver and the audit policy in the Kubernetes documentation.

### Audit (audit) 
Kubernetes audit logs provide a record of the individual users, administrators, or system components that have affected your cluster. For more information, see Auditing
in the Kubernetes documentation.

### Authenticator (authenticator) 
Authenticator logs are unique to Amazon EKS. These logs represent the control plane component that Amazon EKS uses for Kubernetes Role-Based Access Control
(RBAC) authentication using IAM credentials. For more information, see Cluster Management.

### Controller manager (controllerManager) 
The controller manager manages the core control loops that are shipped with Kubernetes. For more information, see kube-controller-manager
in the Kubernetes documentation.

### Scheduler (scheduler) 
The scheduler component manages when and where to run Pods in your cluster. For more information, see kube-scheduler
in the Kubernetes documentation.


 

## Threats
## Detection Matrix
