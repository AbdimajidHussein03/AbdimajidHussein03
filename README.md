
<h1 align="center">Hi 👋, I'm Abdimajid</h1>

<h3 align="center">
DevOps & Platform Engineer | AWS • Azure • Kubernetes • Terraform • CI/CD
</h3>

<p align="center">
Building reliable cloud infrastructure, automated delivery pipelines and scalable container platforms.
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/abdimajidhussein03/">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:abdimajid819@gmail.com">
    <img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://abdimajid.co.uk">
    <img src="https://img.shields.io/badge/Portfolio-Visit_Website-24292F?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" />
  </a>
</p>

---

## About Me

I'm a **DevOps and Platform Engineer** with a Computer Science background, focused on building reliable cloud infrastructure, automating software delivery and improving the way applications are deployed and operated.

My work spans **AWS and Microsoft Azure**, with a strong focus on **Kubernetes, Terraform, CI/CD, GitOps and observability**. I design and build infrastructure that brings together cloud networking, container orchestration, deployment automation and monitoring, with an emphasis on maintainability, security and operational reliability.

Alongside building end-to-end cloud platforms, I contribute to infrastructure and platform engineering work with **Scottish Tech Army**, supporting cloud-hosted services and improvements to operational monitoring.

I'm particularly interested in the engineering behind dependable systems: how infrastructure is structured, how changes move safely into an environment and how platforms behave when workloads fail or demand increases.

---

## Tech Stack

### Cloud & Infrastructure

<p>
  <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white" alt="AWS" />
  <img src="https://img.shields.io/badge/Microsoft_Azure-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Microsoft Azure" />
  <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white" alt="Terraform" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux" />
</p>

### Containers & Orchestration

<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white" alt="Kubernetes" />
  <img src="https://img.shields.io/badge/Amazon_EKS-FF9900?style=for-the-badge&logo=amazoneks&logoColor=white" alt="Amazon EKS" />
  <img src="https://img.shields.io/badge/Azure_AKS-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure AKS" />
  <img src="https://img.shields.io/badge/Amazon_ECS-FF9900?style=for-the-badge&logo=amazonecs&logoColor=white" alt="Amazon ECS" />
  <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=helm&logoColor=white" alt="Helm" />
</p>

### CI/CD & GitOps

<p>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/Argo_CD-EF7B4D?style=for-the-badge&logo=argo&logoColor=white" alt="Argo CD" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Azure_Container_Registry-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Azure Container Registry" />
</p>

### Scripting & Automation

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash" />
</p>

### Observability & Security

<p>
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=for-the-badge&logo=grafana&logoColor=white" alt="Grafana" />
  <img src="https://img.shields.io/badge/Alertmanager-E6522C?style=for-the-badge&logo=prometheus&logoColor=white" alt="Alertmanager" />
  <img src="https://img.shields.io/badge/NGINX-009639?style=for-the-badge&logo=nginx&logoColor=white" alt="NGINX" />
  <img src="https://img.shields.io/badge/Trivy-1904DA?style=for-the-badge&logo=aqua&logoColor=white" alt="Trivy" />
</p>

---

## Featured Projects

### Aegis Platform | Azure Kubernetes & Platform Engineering

Designed and built a **production-style Kubernetes application platform on Microsoft Azure**, integrating Infrastructure as Code, multi-service container orchestration, CI/CD, GitOps, observability and workload resilience.

The platform hosts **Hi.Events**, an event management application consisting of a frontend, backend API, PostgreSQL, Redis, background workers and scheduled jobs.

- Provisioned Azure infrastructure using **modular Terraform**, including AKS, Azure Container Registry, virtual networking, NAT Gateway, network security groups and managed identity
- Orchestrated multiple interconnected container workloads using **Kubernetes Deployments, Services, StatefulSets, persistent storage and Helm**
- Implemented **GitHub Actions CI workflows** for frontend and backend builds and security checks, with **Argo CD** managing GitOps-based application deployments
- Deployed **Prometheus, Grafana and Alertmanager** to monitor Kubernetes workloads, resource utilisation and cluster health
- Configured **readiness and liveness probes**, CPU and memory requests and limits, and Horizontal Pod Autoscaling
- Validated workload recovery through controlled Pod deletion, observing a replacement become Ready in approximately **16 seconds**
- Tested CPU-based autoscaling under load, successfully scaling the frontend from **1 to 2 replicas and back to 1** as demand changed

**`Azure` · `AKS` · `Terraform` · `Kubernetes` · `Helm` · `GitHub Actions` · `Argo CD` · `Prometheus` · `Grafana` · `HPA`**

[**View Aegis Platform →**](https://github.com/AbdimajidHussein03/aegis-platform)

---

### Production-Style Kubernetes Platform | Amazon EKS

Built an end-to-end Kubernetes platform on **Amazon EKS**, integrating Infrastructure as Code, CI/CD automation, GitOps, container security and observability.

- Provisioned AWS infrastructure and the EKS cluster using **Terraform**
- Deployed and managed Kubernetes workloads using **Helm**
- Implemented GitOps delivery through **Argo CD**
- Built automated **GitHub Actions CI/CD pipelines**
- Integrated container vulnerability scanning using **Trivy**
- Configured monitoring and dashboards using **Prometheus and Grafana**

**`AWS` · `Amazon EKS` · `Kubernetes` · `Terraform` · `Helm` · `Argo CD` · `GitHub Actions` · `Prometheus` · `Grafana` · `Trivy`**

[**View EKS Project →**](https://github.com/AbdimajidHussein03/eks-project)

---

### Snipe-IT Asset Management Platform | Amazon ECS Fargate

Deployed a containerised **Snipe-IT asset management application** on AWS ECS Fargate, combining automated infrastructure provisioning, secure networking and continuous delivery.

- Provisioned AWS infrastructure using **Terraform**, including VPC networking, Application Load Balancer, RDS MySQL, ECR, Route 53 and ACM
- Built **GitHub Actions CI/CD pipelines** for container image builds and infrastructure deployment using AWS OIDC authentication
- Designed a container architecture using private subnets, security groups, HTTPS and managed database infrastructure
- Configured **ECS Fargate** to run application workloads behind an Application Load Balancer

**`AWS` · `ECS Fargate` · `Terraform` · `Docker` · `GitHub Actions` · `RDS` · `ECR` · `Route 53`**

[**View ECS Project →**](https://github.com/AbdimajidHussein03/ecs-project)

---

## Let's Connect

I'm open to opportunities in **DevOps Engineering, Platform Engineering and Cloud Infrastructure**, with a particular interest in Kubernetes platforms, infrastructure automation and reliable software delivery.

<p>
  <a href="https://www.linkedin.com/in/abdimajidhussein03/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:abdimajid819@gmail.com">
    <img src="https://img.shields.io/badge/Email-Contact_Me-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://abdimajid.co.uk">
    <img src="https://img.shields.io/badge/Portfolio-View_Projects-24292F?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portfolio" />
  </a>
</p>


