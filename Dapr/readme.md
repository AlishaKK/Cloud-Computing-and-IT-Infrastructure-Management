### Dapr
Dapr in Kubernetes acts as an **application-level sidecar** that provides common distributed system capabilities (like service discovery, state management, pub/sub) to your containerized applications running in Kubernetes, simplifying their development and making them more resilient and scalable without tightly coupling them to Kubernetes-specific APIs.


* **Service Invocation:** Direct communication (HTTP/gRPC) between services.
* **Pub/Sub:** Asynchronous messaging between services.
* **Workflow:** Orchestrate long-running, fault-tolerant business processes.
* **State Management:** Store service data as key-value pairs.
* **Bindings:** Connect to external systems for events (input) and actions (output).
* **Actors:** Implement stateful, object-based microservices.
* **Secrets Management:** Securely retrieve sensitive information.
* **Configuration:** Get and subscribe to application configuration.
* **Resiliency:** Add fault-tolerance to Dapr API calls.
* **Cryptography:** Encrypt and decrypt data.
* **Jobs:** Schedule and manage background tasks.
* **Conversation:** Securely interact with Large Language Models (LLMs).


documentation:

https://docs.dapr.io/getting-started/quickstarts/
