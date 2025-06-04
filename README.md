# Cloud Security Misconfiguration Analyzer

A theoretical research study exploring the identification and mitigation of security misconfigurations in cloud-native environments. This paper introduces a framework grounded in DevSecOps practices, infrastructure-as-code (IaC) scanning, policy-as-code enforcement, and artifact verification, contributing to the enhancement of secure cloud deployment strategies.

---

## 📄 Abstract

This research presents a structured approach to understanding security misconfigurations in contemporary cloud-native systems. It highlights the key vulnerability vectors introduced through Terraform, Kubernetes manifests, and containerized deployment scripts, and proposes a layered analyzer incorporating tools such as Open Policy Agent (OPA), Trivy, and Sigstore to facilitate early detection and policy compliance enforcement.

The study also emphasizes the importance of left-shifted security integration in DevOps pipelines, focusing on automating configuration audits, reducing security debt, and aligning deployments with industry standards.

---

## 📚 Repository Contents

* **Research Paper:** [`paper/CNIT_581ACC_Research_Paper_Spring25_Tarun_Aiyappa.pdf`](./paper/CNIT_581ACC_Research_Paper_Spring25_Tarun_Aiyappa.pdf)
* **Key Topics:**

  * Security debt in cloud-native systems
  * Infrastructure-as-Code (IaC) vulnerability patterns
  * DevSecOps automation
  * Policy-as-Code (OPA & Rego)
  * Container scanning using Trivy
  * Artifact integrity verification using Sigstore
  * Secure pipeline architecture for multi-cloud compliance

---

## 🎓 Academic Context

This research was authored as part of CNIT 581ACC: Advanced Cloud Computing during the Spring 2025 semester at Purdue University. It is a theoretical and conceptual extension of broader academic work on IoT and Digital Twin security. The insights gained here reinforce the necessity of proactive misconfiguration detection mechanisms as cloud infrastructure scales.

While no codebase is provided, this repository serves as a reference and inspiration for researchers and practitioners aiming to strengthen security enforcement in CI/CD environments.

---

## 📜 License

This research work is released under the MIT License. See the [LICENSE](./LICENSE) file for more details.
