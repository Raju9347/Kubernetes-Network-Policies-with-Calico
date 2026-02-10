
**Why Use Network Policies**

**Security:** Prevent unauthorized Pod‑to‑Pod communication.

**Isolation:** Ensure sensitive workloads (e.g., databases) only accept traffic from specific Pods.

**Compliance:** Enforce least‑privilege networking in regulated environments.

**Control Egress:** Restrict Pods from calling external services unless explicitly allowed.


**🔎 How They Work**
You define a NetworkPolicy YAML that specifies:

**Pod selector →** which Pods the policy applies to.

**Ingress rules →** what inbound traffic is allowed.

**Egress rules →** what outbound traffic is allowed.

**List of kubectl cli**

 kubectl get pods,svc
 kubectl exec -it pod/frontend
 kubectl exec -it pod/frontend sh
 kubectl exec -it pod/frontend -- sh
 kubectl get pods
 kubectl exec -it pod/backend -- sh
 kubectl get pods
 network.yml
 vi network.yml
 kubectl apply -f network.yml 
 kubectl get netpool
 kubectl get netpol
 kubectl describe netpol mysql
 kubectl describe netpol db-test
 kubectl exec -it pod/backend -- sh
 kubectl get pods
 kubectl exec -it pod/frontend -- sh
