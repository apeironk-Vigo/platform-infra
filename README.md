Platform Engineering Sandbox
This repository serves as a personal laboratory for exploring and implementing modern, cloud-native infrastructure patterns. I use this space to experiment with architectural trade-offs, automate deployment workflows, and prototype resilient, scalable systems.
Core Focus Areas
 Infrastructure-as-Code (IaC): Developing reusable, modular Terraform configurations to manage cloud resources.
 Container Orchestration: Advanced Kubernetes configurations and management patterns.
 Message Bus Modernization: Exploring the transition from legacy Zookeeper-dependent Kafka clusters to modern, streamlined KRaft-based architectures.
 CI/CD Pipeline Automation: Building robust GitHub Actions workflows to validate, lint, and deploy infrastructure changes.
Featured Projects
1. Kafka Migration to KRaft
 Goal: Modernize message-bus architecture by removing the Zookeeper dependency.
 Challenge: Migrating coordination services without sacrificing reliability or data integrity.
 Outcome: Successfully implemented Kafka in KRaft mode, significantly reducing the system's operational complexity and decreasing the number of moving parts requiring management.
 Impact: A cleaner, container-native deployment that is easier to observe, scale, and debug.
2. Nginx Service Deployment
 Goal: Automate the scaling of web services within a Kubernetes environment.
 Outcome: Implemented an Nginx deployment configuration scaled to 3 replicas via Autopilot, ensuring high availability and load distribution.
Purpose
This repository is a "work in progress." It reflects my ongoing journey in Platform Engineering—focusing on simplicity, automation, and system observability.

