# Resiliency and Security Evaluation of Azure Using Fault Injection

## 📌 Overview
Security and resilience are critical in cloud computing, where system failures can disrupt services and compromise data. This project explores **chaos engineering** techniques to evaluate and enhance the **resilience of Azure-based systems** through controlled **fault injection experiments**.

## 🛠️ Technologies Used
- **Microsoft Azure** (Azure Monitor, Log Analytics, Azure Security Center)
- **Chaos Engineering** (Fault Injection)
- **Python & Azure CLI** (Automation and Analysis)
- **Azure Chaos Studio** (Failure Simulations)
- **Azure Blob Storage & NSG** (Security Testing)

## 🔬 Research Objectives
- Simulating **real-world cloud failures** (e.g., unauthorized access attempts, misconfigured security rules).
- Analyzing **Azure’s built-in resiliency mechanisms**.
- Identifying **weak points** in cloud infrastructure.
- Proposing **improvements for failure detection and recovery**.

## 📊 Key Findings
- **Blob Storage Vulnerabilities:** Publicly accessible sensitive data, missing audit logs.
- **NSG Rule Modifications:** Unintended priority shifts, blocking of critical API traffic.
- **System Limitations:** Log monitoring gaps, scalability issues in multi-region setups.
- **Proposed Solutions:** Automated security policies, improved alerting mechanisms.

## 🚀 How to Use
1. Clone the repository:  
   ```sh
   git clone https://github.com/yourusername/azure-resilience-testing.git

