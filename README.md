<h1 align="center">Hi, I'm Yasser Metwally 👋</h1>
<h3 align="center">DevOps & SysOps Engineer</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=0084D8&center=true&vCenter=true&width=600&lines=DevOps+%26+SysOps+Engineer;Linux+%C2%B7+VMware+%C2%B7+Kubernetes;Automate+everything+with+Ansible+%26+CI%2FCD;Monitor+%C2%B7+Back+up+%C2%B7+Recover" alt="Typing SVG" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/yasser-fawzy"><img src="https://img.shields.io/badge/LinkedIn-yasser--fawzy-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:yasser.metwallykaka@gmail.com"><img src="https://img.shields.io/badge/Email-Contact%20me-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <img src="https://img.shields.io/badge/Location-Alexandria%2C%20Egypt-555?style=flat&logo=googlemaps&logoColor=white" alt="Location">
  <img src="https://komarev.com/ghpvc/?username=yaserkaka&style=flat&color=0e75b6&label=Profile+views" alt="Profile views">
</p>

---

## 🙋‍♂️ About Me

DevOps & SysOps Engineer at **Andalusia Health and Business Solutions**. I keep hybrid Linux and Windows infrastructure on VMware vSphere running, automate the repetitive work with **Ansible, Bash, and Python**, and ship services through **CI/CD pipelines** into containers and Kubernetes.

My focus: reliable infrastructure, automation over manual work, clear monitoring, and fast root cause analysis to cut MTTR.

---

## ⚙️ What I Do

- 🖥️ **SysOps:** Run production RHEL and Ubuntu servers across 3 ESXi hosts (24 VMs) at 99.9% availability: LVM storage, kernel updates, patching, and security hardening
- 🤖 **Automation:** Ansible playbooks and Bash/Python scripts for provisioning, health checks, and scheduled patching, with no manual per-host drift
- 🧱 **Golden images:** Automated OS images (Packer, Sysprep, DISM) that cut new VM provisioning time by 60%+
- 🚀 **CI/CD & containers:** Docker images and Azure DevOps / GitHub Actions pipelines (repos, artifact registries, build agents) with zero-downtime rolling updates
- ☸️ **Kubernetes:** Helm deployments, NGINX ingress, TLS, autoscaling, ConfigMaps/Secrets, ClusterIP/NodePort, CoreDNS
- 📈 **Observability:** Prometheus, Grafana, and New Relic dashboards and alerts for saturation, latency, and availability
- 💾 **Backup & DR:** Veeam backup jobs, restore testing, and disaster recovery
- 🌐 **Networking & security:** DNS, DHCP, VLANs, FortiGate firewall rules, site-to-site and client VPNs
- 🔍 **Incident response:** Root cause analysis across OS, network, and port-level faults

---

## 🛠️ Tech Stack

**Linux & OS**<br>
![RHEL](https://img.shields.io/badge/RHEL-EE0000?style=flat&logo=redhat&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)
![Windows Server](https://img.shields.io/badge/Windows%20Server-0078D6?style=flat&logo=windows&logoColor=white)

**Automation & IaC**<br>
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat&logo=ansible&logoColor=white)
![Packer](https://img.shields.io/badge/Packer-02A8EF?style=flat&logo=packer&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

**Containers & orchestration**<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat&logo=kubernetes&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat&logo=helm&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-009639?style=flat&logo=nginx&logoColor=white)

**CI/CD & cloud**<br>
![Azure DevOps](https://img.shields.io/badge/Azure%20DevOps-0078D7?style=flat&logo=azuredevops&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)

**Virtualization**<br>
![VMware](https://img.shields.io/badge/VMware%20vSphere%20%2F%20ESXi-607078?style=flat&logo=vmware&logoColor=white)
![KVM](https://img.shields.io/badge/KVM-FF6600?style=flat&logo=linux&logoColor=white)

**Monitoring**<br>
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![New Relic](https://img.shields.io/badge/New%20Relic-1CE783?style=flat&logo=newrelic&logoColor=black)

**Networking, security & backup**<br>
![FortiGate](https://img.shields.io/badge/FortiGate-EE3124?style=flat&logo=fortinet&logoColor=white)
![Veeam](https://img.shields.io/badge/Veeam-00B336?style=flat&logo=veeam&logoColor=white)
![Networking](https://img.shields.io/badge/TCP%2FIP%20·%20DNS%20·%20DHCP%20·%20VLANs%20·%20VPN%20·%20TLS-444?style=flat)

---

## 🚀 Featured Projects

| Project | What it does | Stack |
|---|---|---|
| 🧱 [Server_Golden-Image](https://github.com/yaserkaka/Server_Golden-Image) | One Packer build produces a hardened Ubuntu 24.04 image; every KVM/vSphere clone boots as a unique server and configures itself for its role (HPC compute node, Kubernetes node). 3-layer verification (CI, offline, live) plus STREAM/OSU benchmarks. | Packer, Bash, Ubuntu, KVM, vSphere |
| ☸️ Containerized Platform | Multi-service app on Kubernetes with Helm, NGINX ingress, TLS, and autoscaling; GitHub Actions pipeline with zero-downtime rolling updates; Prometheus/Grafana monitoring with alert rules. | Docker, Kubernetes, Helm, GitHub Actions, Prometheus, Grafana |
| 🩺 [Linux-Server-Health-check](https://github.com/yaserkaka/Linux-Server-Health-check) | Scripted health checks for Linux servers. | Bash |

---

## 📜 Certifications & Training

- Red Hat System Administration I (RH124)
- IBM DevOps and Software Engineering (Coursera)
- Introduction to High Performance Computing (Maharatech)
- Certified Kubernetes Administrator (CKA), in preparation
- AWS Solutions Architect – Associate, in training
