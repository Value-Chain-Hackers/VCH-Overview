---
title: "My Multi-Format Slides"
format:
  revealjs: default
  pdf: default
  pptx: default
---

### **Vision & Value Proposition**

**🚀 Empowering Collaborative Research in Supply Chain & Supply Chain Finance**
A fully open-source platform enabling:

* Frictionless **data sharing** between academia, students & industry
* Local **AI research workflows** with GPU acceleration & reproducibility
* Academic neutrality & trust through transparent architecture
* Federated and secure **hybrid deployment** using DAT Linux
* Modular system supporting large datasets, privacy, and openness

**🔍 Goal**: Build a research commons that advances sustainable, reproducible, and industry-relevant insights.

---

## 🎯 Hook (Updated)

> **“What if we could rebuild trust in research and fix broken supply chains — not by spending millions on new tech, but by connecting what we already have?”**

We’re building an open-source platform that makes it *easy* for academics, students, and industry to share data, run AI locally, and collaborate transparently — without giving up control or privacy.

---

## **What We're Building**

> **An Open AI-Powered Research Platform for Supply Chain & Finance**

* Hybrid system running on **DAT Linux**, using trusted tools:
  * 📁 **Nextcloud** for secure data sharing
  * 📊 **JupyterHub** for notebooks & AI
  * 🔄 **Git + CI/CD** for reproducibility
* All **open-source**, modular, and built to scale
* Designed for **students, researchers, and industry** to co-develop real solutions

> 🔧 **Still building — and looking for bold collaborators.**

---

## **Why We’re Building It**

> **To end the siloed, broken status quo**

* Research is stuck behind paywalls, privacy fears, and unreproducible claims
* Companies want answers, not black-box AI
* Students need real-world, real-data experience

We're designing this platform to:

* Restore **trust** in academic neutrality
* Make **data collaboration frictionless**
* Enable **responsible, local AI** you can actually use

---

## **What’s the Payoff?**

> **A shared platform, with shared gains**

✅ Companies: **reduced risk**, better forecasting  
✅ Researchers: **faster collaboration**, real-world impact  
✅ Students: **hands-on skills**, open science mindset  
✅ Society: **more sustainable, transparent supply chains**

> **You can’t solve systemic problems in silos.  
> We’re building the platform that brings everyone together.**


### **System Architecture Overview**



**Tech Stack Highlights:**
🧠 JupyterHub (GPU-enabled), 🗃️ Nextcloud + Ceph, 🧬 NiFi ETL, 🧪 Git-based CI/CD, 🔐 Keycloak SSO

---

### **Data & AI Workflow**

1. **Ingestion**: Apache NiFi fetches data (APIs, CSVs, ERP, IoT) → Nextcloud
2. **Cataloging**: Apache Atlas/Amundsen index data + metadata
3. **Analysis**: JupyterHub (Python, R) with containerized environments (Docker/Conda)
4. **ML Training**: GPU-powered workflows via K8s + CI/CD (model, score, deploy)
5. **Results**: Published via dashboards (Voila, Superset) + versioned with Git/DVC

🔁 Fully reproducible with automated pipelines + environment tracking
🔒 Access controlled by user roles (researcher, student, partner)

---

### **Access, Control & Collaboration**

* 🎯 **Role-based access** with Keycloak SSO (academics, students, partners)
* 📂 Nextcloud group folders, fine-grained ACLs, watermarking, logging
* 🧾 Data usage licensing & metadata tagging (CC-BY, research-only, etc.)
* 🔄 Versioned datasets + model artifacts using DVC and Git
* 🤝 Built-in collaboration (Nextcloud Talk, shared notebooks, dashboard links)

**Open Source Means:**

* No vendor lock-in
* Maximum trust & transparency
* Local control of sensitive data

---