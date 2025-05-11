
### Virtualization in Cloud Computing 

**What is Virtualization?**
Virtualization creates virtual versions of physical resources (like servers, storage, or networks) on a single machine, allowing multiple virtual machines (VMs) to run independently with their own operating systems and apps. It’s a key part of cloud computing, enabling **Infrastructure as a Service (IaaS)**.

**How It Works**:
- A **hypervisor** (software) divides a physical computer’s resources (CPU, RAM, storage) among multiple VMs.
- Each VM acts like a separate computer but shares the same physical hardware.
- **Types of Hypervisors**:
  - **Type 1**: Runs directly on hardware (e.g., VMware ESXi).
  - **Type 2**: Runs on top of an operating system (e.g., VirtualBox).

**Why It’s Important in Cloud Computing**:
- **Efficient Resource Use**: Runs multiple VMs on one server, reducing waste.
- **Cost Savings**: Fewer physical machines mean lower hardware and power costs.
- **Flexibility**: Easily create, move, or scale VMs.
- **Security**: Isolates VMs, so issues in one don’t affect others.
- **Fast Recovery**: VMs can be backed up or restored quickly.

**Types of Virtualization**:
1. **Server Virtualization**: Splits a server into multiple virtual servers (e.g., VMware vSphere).
2. **Desktop Virtualization**: Creates virtual desktops accessible from any device (e.g., Amazon WorkSpaces).
3. **Network Virtualization**: Runs multiple virtual networks on one physical network (e.g., Google Cloud).
4. **Storage Virtualization**: Combines storage from multiple sources into one system (e.g., Amazon S3).
5. **Application Virtualization**: Runs apps remotely without local installation (e.g., Microsoft Azure).
6. **Data Virtualization**: Unifies data from multiple sources for easy access (e.g., Oracle solutions).

**Benefits**:
- Saves costs and resources.
- Scales quickly and supports remote access.
- Improves security and disaster recovery.
- Runs multiple operating systems on one machine.

**Drawbacks**:
- High initial setup cost.
- Requires skilled staff to manage.
- Data hosted on third-party servers may face security risks.

**Example**:
A company needs four servers for different tasks (e.g., website, database, payroll). Instead of buying four physical servers, it uses virtualization to run four VMs on one server, saving money and simplifying management.

**Virtualization vs. Cloud Computing**:
- **Virtualization**: Technology to create virtual resources on a single machine.
- **Cloud Computing**: Service model using virtualization to deliver resources (like servers, storage) over the internet.

https://www.geeksforgeeks.org/virtualization-cloud-computing-types/

https://youtu.be/MnU-t31MtRY?si=K8sWLfYQktW0Frvg
