![image](https://github.com/user-attachments/assets/362a8f03-ed56-4598-afc4-46dd97eed567)


**Control Plane (Master Node):**

* **Client (kubectl, UI, CLI):** Tools that users interact with to manage the Kubernetes cluster.
* **API SERVER:** The central control plane component that exposes the Kubernetes API.
* **Scheduler:** Assigns newly created pods to nodes for execution.
* **ETCD:** A distributed key-value store that serves as Kubernetes' backing store for all cluster data.
* **Controller Manager:** Runs controller processes that regulate the state of the Kubernetes cluster.
* **MASTER:** The control plane node(s) that manage the Kubernetes cluster.

**Worker Node:**

* **Kubelet:** An agent that runs on each node and ensures that containers are running in pods.
* **Kube-proxy:** A network proxy that runs on each node, implementing Kubernetes service concepts.
* **Container-runtime:** The underlying software (e.g., Docker, containerd) that runs containers.
* **Worker Node:** A machine in the Kubernetes cluster that runs your applications in pods.
* **Container Node:** Another term often used interchangeably with "Worker Node," referring to a machine that runs containers managed by Kubernetes.

**Kubernetes Object:**

* **Pod:** The smallest deployable unit in Kubernetes, representing a group of one or more containers that share storage and network resources.




Documentation:

https://kubernetes.io/docs/concepts/architecture/

