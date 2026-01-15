# multi-cloud-security-broken-bridge

## Overview
  
The exercise simulates a **multi-cloud incident response and recovery scenario** where a fragmented application spans **Google Cloud Platform (GCP)** and **Amazon Web Services (AWS)**.

A frontend application was deployed on GCP, while the backend database was deployed on AWS. Due to a misconfigured or severed network path, the application became unreachable. The objective was to reconstruct the intended architecture, diagnose the failure, securely restore connectivity, and recover the mission payload (flag).

All work was performed in **instructor-provided sandbox environments** for educational purposes only.

---

## Learning Objectives
By completing this lab, the following objectives were achieved:

- Perform reconnaissance using the **GCP CLI**
- Locate and retrieve deployment artifacts from **Google Cloud Storage**
- Reconstruct a broken **multi-cloud network path**
- Diagnose cloud connectivity failures (timeouts, security group misconfigurations)
- Apply **least-privilege and minimal-exposure** networking fixes
- Reflect on security posture improvements across IAM, secrets, and network design

---

## Cloud Platforms & Tools
- **Cloud Providers:**  
  - Google Cloud Platform (GCP)  
  - Amazon Web Services (AWS)

- **Tools & Services:**  
  - `gcloud` CLI  
  - Google Cloud Storage  
  - Google Compute Engine (VM)  
  - AWS EC2 & Security Groups  
  - AWS CloudFormation  

---

