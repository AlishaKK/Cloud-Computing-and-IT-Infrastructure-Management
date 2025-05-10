### **Kubernetes:**


Kubernetes is a system for automatically managing and scaling applications that run in containers. It helps deploy, maintain, and grow these applications efficiently across a set of computers (nodes).

  ![image](https://github.com/user-attachments/assets/362a8f03-ed56-4598-afc4-46dd97eed567)

  


**Why Use It?**

* **Auto-scaling:** Handles traffic spikes.
* **High Availability:** Restarts failing containers.
* **Easy Deployments:** Simplifies updates/rollbacks.
* **Efficient Resources:** Optimizes hardware use.
* **Less Complexity:** Automates container management.
* **Dev Focus:** Lets developers build, not manage.
* **Consistent Platform:** Works anywhere.

**Before Kubernetes (Traditional):**

* **Manual:** Deployment and scaling were manual.
* **Inconsistent:** Environments varied.
* **Low Resource Use:** Servers often underutilized.
* **Downtime Risk:** Failures meant manual fixes.
* **Complex:** Managing distributed apps was hard.
  



![image](https://github.com/user-attachments/assets/06001415-96b2-4b0c-a704-1e0d6c7cd431)







**Control Plane (Master Node):**

* **Client (kubectl, UI, CLI):** Tools that users interact with to manage the Kubernetes cluster.
* **API SERVER:** The central control plane component that exposes the Kubernetes API.
* **Scheduler:** Assigns newly created pods to nodes for execution.
* **ETCD:** A distributed key-value store that serves as Kubernetes' backing store for all cluster data.
* **Controller Manager:** Runs controller processes that regulate the state of the Kubernetes cluster.
* **MASTER:** The control plane node(s) that manage the Kubernetes cluster.

**Worker Node:**

* **Kubelet:** An agent that runs on each node and ensures that containers are running in pods.
* **Kube-proxy:** A network proxy that runs on each node, implementing Kubernetes service concepts.(load balance)
* **Container-runtime:** The underlying software (e.g., Docker, containerd) that runs containers.
* **Worker Node:** A machine in the Kubernetes cluster that runs your applications in pods.
* **Container Node:** Another term often used interchangeably with "Worker Node," referring to a machine that runs containers managed by Kubernetes.

**Kubernetes Object:**

* **Pod:** The smallest deployable unit in Kubernetes, representing a group of one or more containers that share storage and network resources.


![image](https://github.com/user-attachments/assets/d9754968-ef6e-4f3a-a202-1238c8663c65)

imagine a Cluster as a group of computers working together.

Each computer in the group is called a Node.

Inside each Node, you can have one or more Pods. Think of a Pod as a small box where your applications run.

So, a Cluster has many Nodes, and each Node can have many Pods running your software. Simple!


![image](https://github.com/user-attachments/assets/484331a1-7e68-4461-970a-bc0624090627)

 think of a Pod as a single apartment.

Inside that Pod (apartment), you can have one or more Containers (rooms).

So, a Pod is the smallest unit in Kubernetes, and it can hold one or more running Containers. Easy peasy!




Documentation:

https://kubernetes.io/docs/concepts/architecture/

Youtube video in English :

https://youtu.be/B_X4l4HSgtc?si=gCUD8hgKItndTTb3


Youtybe Video in Urdu:

https://youtu.be/7ZObcqEq7hU?si=IQMkn_DiXzKygZ5h

![image](https://github.com/user-attachments/assets/809e305e-c342-496a-bd79-e1d6d60c2e85)


### Argo CD

Argo CD automates Kubernetes application deployments using GitOps. It continuously monitors Git repositories and syncs the desired application state to your clusters, ensuring consistency, reliability, and easier rollbacks.

![image](https://github.com/user-attachments/assets/b1f6d1df-a58e-4078-b29d-132b46c162db)


Documentation:

https://argo-cd.readthedocs.io/en/stable/

Youtube Video:

https://youtu.be/ZLZLheMfegM?si=i4FZff2NVQKfQNPW

