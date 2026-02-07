
# 🚀 AWS AI Cloud Engineer Journey

This repository documents my 6-month intensive journey to becoming an AWS AI Cloud Engineer. It includes hands-on labs, architectural patterns, and deployment strategies for AI/ML solutions on the AWS Cloud.

---

## 📅 Day 1: Cloud Workstation & Environment Setup

On the first day, I successfully provisioned and configured a professional-grade cloud development environment. This setup serves as the foundation for all upcoming AI and data engineering tasks.

### **1. Infrastructure Management (EC2)**
* **Provisioning:** Deployed an **AWS EC2 (Ubuntu)** instance to serve as a high-performance remote workstation.
* **Connectivity:** Established secure access via **MobaXterm** using SSH Key Pairs (.pem files).
* **Cost Optimization:** Implemented a lifecycle strategy to **Stop** instances during idle hours to minimize AWS consumption costs.
* **Network Handling:** Mastered handling dynamic **Public IP** assignments and connectivity troubleshooting.

### **2. AWS CLI & Security Configuration**
* **Installation:** Successfully installed and verified **AWS CLI v2** on the remote Linux environment.
* **IAM Integration:** Configured CLI access using **IAM User credentials**, adhering to the **Principle of Least Privilege (PoLP)**.
* **Multi-Profile Management:** Set up **Named Profiles** (`aws configure --profile client_name`) to securely manage resources across multiple client accounts from a single terminal.
* **S3 Management:** Verified configuration by managing and auditing S3 buckets directly via the command line.

### **3. AI Development Stack (Workstation Setup)**
Installed the essential toolchain required for modern AI/ML development:
* **Python 3 & Pip:** Configured the environment for managing deep learning libraries like PyTorch and Scikit-learn.
* **Git:** Initialized version control for seamless integration with this GitHub repository.
* **Docker Engine:** Installed Docker to containerize AI applications, ensuring "Write Once, Run Anywhere" consistency across environments.

### **4. Remote Development with VS Code**
* **Remote-SSH Integration:** Configured **VS Code Remote-SSH** extension to enable a local IDE experience while executing heavy workloads on AWS hardware.
* **SSH Config Optimization:** Streamlined identity management by configuring the local `.ssh/config` file for quick, one-click connections.

### **5. File & Project Management**
* **Structured Workspace:** Created a professional directory hierarchy (`~/projects/ai-client-work`) for organized task management.
* **SFTP Workflow:** Leveraged the MobaXterm SFTP browser for efficient bi-directional file transfers between local and cloud storage.

---

### **🛠 Technical Skills Gained Today:**
- **Cloud Computing:** AWS EC2, IAM, Security Groups.
- **DevOps:** Docker, Git, CLI Automation.
- **Linux Admin:** Package Management (APT), SSH, File Permissions.
- **IDE Optimization:** Remote Development workflows.

---
