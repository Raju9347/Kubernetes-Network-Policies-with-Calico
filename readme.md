
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
