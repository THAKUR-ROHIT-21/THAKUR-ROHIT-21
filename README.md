<p align="center">
  <img src="https://raw.githubusercontent.com/DEVENDRA-5470/DEVENDRA-5470/main/assets/generated/galaxy-header.svg" width="100%" />
</p>

<h1 align="center">Rohit Kumar</h1>

<p align="center">
  <code>DevOps Engineer | AWS • Azure • GCP • Kubernetes • CI/CD</code>
</p>

---

## 🧰 Stack

`AWS` `Azure` `GCP` `Terraform` `Kubernetes` `Docker` `Jenkins` `Git` `GitHub Actions` `Linux` `Bash` `Python` `Flask` `MySQL` `Node.js` `React` `HTML` `CSS` `Prometheus` `Grafana` `Helm`

## 🎯 Focus

DevOps Engineer designing and operating cloud infrastructure, Kubernetes environments, CI/CD pipelines, containerized applications, and observability stacks.

Focused on building reliable and automated infrastructure using AWS, Azure, and GCP — from Infrastructure as Code with Terraform to containerized deployments with Docker and Kubernetes.

Currently working on hands-on Kubernetes operations, cloud infrastructure, Terraform automation, CI/CD with Jenkins and GitHub Actions, and monitoring with Prometheus + Grafana.

## 📁 Case studies

Each project below represents infrastructure and DevOps work I have designed, deployed, automated, and troubleshot — with focus on practical production scenarios rather than only the technology list.

#### ☸️ Kubernetes Cluster

Self-managed Kubernetes cluster with containerized workloads

A multi-node Kubernetes cluster built using kubeadm for hands-on experience with Kubernetes internals, networking, scheduling, storage, and cluster operations.

*Problem* — needed practical experience with Kubernetes components instead of depending only on managed Kubernetes services

*Approach* — configured control-plane and worker nodes with kubeadm, containerd, Calico networking, local-path storage, and NGINX Ingress

*Operations* — Pods, Deployments, Services, ConfigMaps, Secrets, Namespaces, RBAC, Scheduler, Controller Manager, API Server, etcd, Kubelet

*Scheduling* — node affinity, taints and tolerations, resource requests/limits, and troubleshooting unscheduled Pods

*Storage* — PersistentVolumes, PersistentVolumeClaims, StorageClass, and local-path provisioning

`Kubernetes` `kubeadm` `containerd` `Calico` `Ingress` `RBAC`

#### ⚙️ Terraform Cloud Infrastructure

Infrastructure as Code across AWS and GCP

Terraform-based infrastructure for provisioning and managing cloud resources consistently.

*Problem* — manual infrastructure creation is difficult to reproduce, maintain, and scale

*Approach* — created Terraform configurations and reusable modules for VPC networking, subnets, compute instances, storage, and cloud resources

*AWS* — EC2, VPC, IAM, S3, RDS, CloudFront, Route 53, Load Balancer, Auto Scaling

*GCP* — Compute Engine, VPC, subnets, firewall rules, service accounts, and Cloud Storage

*Practice* — providers, variables, outputs, modules, state management, `terraform plan`, `terraform apply`, and targeted deployments

`Terraform` `AWS` `GCP` `VPC` `EC2` `Compute Engine`

#### 🔐 SimpleBank

AWS-native banking application with secure infrastructure

A Flask + MySQL banking application deployed with AWS infrastructure and containerized application services.

*Problem* — required secure communication between application and database without exposing the database publicly

*Approach* — EC2 application layer with private RDS MySQL, VPC networking, security groups, IAM, and AWS Systems Manager

*Security* — private RDS database, restricted security groups, IAM permissions, SSM Session Manager, and port forwarding instead of exposing database ports

*Automation* — Dockerized application deployment with CI/CD and infrastructure automation

`Flask` `MySQL` `EC2` `RDS` `VPC` `IAM` `SSM` `Docker`

#### 🐳 Dockerized Applications

Containerized applications using Docker and Docker Compose

Multiple backend and frontend applications containerized to provide consistent development and deployment environments.

*Problem* — applications can behave differently between development, testing, and production environments

*Approach* — created Dockerfiles and Docker Compose configurations for application services

*Practice* — images, containers, networks, volumes, environment variables, health checks, application dependencies, and multi-container deployments

*Applications* — Flask, Node.js, React, MySQL and other backend services

`Docker` `Docker Compose` `Python` `Flask` `Node.js` `React`

#### 🔄 Jenkins CI/CD

Automated build, test and deployment pipelines

Jenkins pipelines created for automated application delivery and infrastructure workflows.

*Problem* — manual deployment introduces human error and slows down application delivery

*Approach* — implemented declarative Jenkins pipelines with dedicated agents and automated build/deployment stages

*Pipeline* — Git checkout → Build → Test → Docker Build → Deployment → Smoke Test

*Operations* — Jenkins agents, credentials, pipeline stages, environment variables, notifications, and troubleshooting failed builds

`Jenkins` `CI/CD` `Git` `Docker` `Linux`

#### 🚀 GitHub Actions

Automated CI/CD and infrastructure validation

GitHub Actions workflows for application testing, infrastructure validation, AWS authentication, and deployment automation.

*Problem* — needed automated validation before infrastructure and application changes reached deployment

*Approach* — created workflows for testing, smoke testing, Docker builds, AWS authentication, and deployment

*Security* — AWS authentication using IAM roles and OIDC instead of storing long-lived credentials

*Validation* — automated infrastructure and networking smoke tests

`GitHub Actions` `OIDC` `AWS IAM` `Docker` `Python`

#### 📊 Prometheus & Grafana

Kubernetes monitoring and observability

Monitoring stack deployed on Kubernetes using Prometheus, Grafana, and Alertmanager.

*Problem* — infrastructure and application issues need to be detected and investigated quickly

*Approach* — deployed kube-prometheus-stack using Helm

*Monitoring* — nodes, Pods, CPU, memory, workloads, Kubernetes components, and application metrics

*Visualization* — Grafana dashboards for Kubernetes and infrastructure monitoring

*Alerting* — Alertmanager configured for sending notifications when defined conditions are triggered

`Prometheus` `Grafana` `Alertmanager` `Helm` `Kubernetes`

#### ☁️ AWS Two-Tier Banking Architecture

Secure application and database architecture

Two-tier architecture with application services running on EC2 and database services running on private RDS.

*Problem* — database should not be directly reachable from the public internet

*Approach* — public application layer with private database layer using VPC networking and security groups

*Database* — Amazon RDS MySQL deployed privately

*Access* — AWS Systems Manager used for secure server access and database port forwarding

*Security* — IAM, Security Groups, private networking, and restricted inbound/outbound rules

`AWS` `VPC` `EC2` `RDS` `IAM` `SSM`

#### 🌐 Microservices Application

Containerized microservices architecture

A microservices-based application consisting of multiple backend services.

*Services* — Profile Service, Product Service, Order Service, and Payment Service

*Approach* — each service runs independently and is containerized using Docker

*Deployment* — Docker Compose used for local multi-service orchestration and service-to-service communication

*Practice* — service discovery, environment configuration, networking, container health checks, and application troubleshooting

`Microservices` `Docker` `Docker Compose` `Node.js` `Python`

#### 🛠️ Infrastructure Smoke Testing

Automated infrastructure and networking validation

Python-based smoke testing used to verify infrastructure and application connectivity.

*Problem* — infrastructure deployments can succeed while network connectivity or application endpoints remain broken

*Approach* — automated checks for connectivity, application endpoints, ports, and service availability

*Integration* — smoke tests executed through GitHub Actions as part of CI/CD workflows

`Python` `GitHub Actions` `CI/CD` `Networking`

#### 🔐 Cloud & Kubernetes Security

IAM, RBAC and secure infrastructure access

Hands-on implementation of access control across AWS and Kubernetes.

*AWS* — IAM users, IAM roles, policies, security groups, and least-privilege permissions

*Kubernetes* — RBAC, Roles, RoleBindings, ServiceAccounts, Namespaces, and authorization

*Infrastructure* — private networking, restricted ports, firewall rules, and secure service communication

`AWS IAM` `Kubernetes RBAC` `Security Groups` `Linux`

#### 📚 Kubernetes Internals

Hands-on Kubernetes learning and troubleshooting

Built practical understanding of how Kubernetes components work together.

*API Server* — receives and validates Kubernetes API requests

*etcd* — stores the cluster state and configuration

*Scheduler* — decides which worker node should run a Pod

*Controller Manager* — continuously maintains the desired state

*Kubelet* — manages Pods and containers on worker nodes

*Container Runtime* — runs containers on worker nodes

*Networking* — provides communication between Pods, Services, and external clients

`API Server` `etcd` `Scheduler` `Controller Manager` `Kubelet`

---

## 📈 GitHub activity

💬 Open to conversations on DevOps, cloud architecture, Kubernetes, CI/CD, Terraform, monitoring, automation, and production troubleshooting.

### ☁️ Cloud

AWS · Azure · GCP

### ⚙️ Infrastructure

Terraform · Linux · Bash · Networking · IAM

### ☸️ Containers & Orchestration

Docker · Docker Compose · Kubernetes · Helm · Calico · Ingress

### 🔄 CI/CD

Jenkins · GitHub Actions · Git · OIDC

### 📊 Monitoring

Prometheus · Grafana · Alertmanager

### 💻 Development

Python · Flask · Node.js · React · MySQL · HTML · CSS

---

## 👨‍💻 About Me

I'm a DevOps Engineer with hands-on experience in cloud infrastructure, CI/CD automation, Kubernetes, Terraform, Docker, monitoring, and Linux.

I enjoy troubleshooting infrastructure problems, automating repetitive tasks, designing secure cloud architectures, and learning how systems work internally.

My current learning focus is Kubernetes, Terraform, cloud architecture, CI/CD, observability, and production-grade DevOps practices.

---

## 🔗 Connect

**GitHub:** DEVENDRA-5470

**LinkedIn:** Rohit Kumar

**Focus:** DevOps · Cloud · Kubernetes · Terraform · CI/CD · SRE
