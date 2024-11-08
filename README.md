# Interview Question DevOps SRE

Welcome to the **Interview Questions DevOps SRE** repository! This repo contains a collection of  interview questions and topics that every aspiring **DevOps Engineer** and **Site Reliability Engineer (SRE)** should prepare for. The questions are categorized by different DevOps topics including Linux, Git, Ansible, Terraform, AWS, CI/CD, Kubernetes, and Docker.

This repository is designed to help you understand key DevOps and SRE concepts and to give you a deeper insight into the tools and practices used in the field. Whether you're preparing for your first interview or you're looking to solidify your knowledge, this resource will provide valuable insights.

## Table of Contents

1. [Linux, Git, and Ansible](#linux-git-and-ansible)
2. [Terraform](#terraform)
3. [AWS](#aws)
4. [CI/CD](#cicd)
5. [Kubernetes](#kubernetes)
6. [Docker](#docker)
7. [Contribute](#contribute)

## Linux, Git, and Ansible

- **Crontab File / Config - Location**  
  Where is the crontab file or configuration stored?

- **What is Ansible Inventory?**  
  Define what an Ansible inventory is and how it works.

- **How will you deploy changes to worker nodes using Ansible?**  
  Provide a detailed step-by-step guide on deploying changes to worker nodes with Ansible.

- **Difference between `git reset` and `git revert`**  
  Compare and contrast the functionality of `git reset` and `git revert`.

- **Restoring Changes to a Specific Commit**  
  There are four commits in Git, and you want to restore changes to the second commit without creating any new commits. How would you approach this?

- **How Nginx Works**  
  What is Nginx, how does it work, and how do you configure it using `.config` files?

## Terraform

- **What Happens When Two People Try to Perform the Same Operation at the Same Time?**  
  Explain in detail what happens when two users attempt to perform the same operation in Terraform, and how MongoDB can help in this scenario.

- **Provisioners in Terraform**  
  What are provisioners in Terraform, and how do they work?

- **Null Resources in Terraform**  
  What are null resources in Terraform and how are they used?

- **Taints in Terraform**  
  What are taints in Terraform, and how do they affect resource management?

## AWS

- **How Will You Access the EC2 Instance if the Key-Pair Login (.pem) Files Are Accidentally Deleted?**  
  Provide a detailed solution for accessing an EC2 instance when the `.pem` key is deleted.

- **Broadcast vs. Loopback**  
  Explain the difference between broadcast and loopback networking.

- **How to Upload a File to S3 from an EC2 in a Different AWS Account?**  
  What steps would you follow to upload a file from an EC2 instance in one AWS account to an S3 bucket in another AWS account?

- **How to SSH into an EC2 Instance in a Private Subnet?**  
  Provide the steps for accessing an EC2 instance in a private subnet.

- **How to Recover a Deleted Snapshot of 10GB?**  
  Explain how you would recover a deleted snapshot in AWS.

- **R53 A-Name and C-Name**  
  What is the difference between an A-name and a C-name record in Route 53?

- **Can You Assign a Private IP to a NAT Gateway?**  
  Is it possible to assign a private IP to a NAT gateway in AWS? Explain why or why not.

## CI/CD

- **Service Mesh**  
  What is a service mesh, and how does it help in managing microservices communication?

- **Managing Space Issues on Jenkins by Building and Pulling Docker Images**  
  How do you manage disk space issues in Jenkins when you are building and pulling a lot of Docker images?

- **How Do You Secure a Jenkins Server?**  
  What security measures would you implement to secure a Jenkins server?

- **Jenkins Master Node Setup**  
  How do you set up a Jenkins Master Node?

- **How to Set User and User Permissions on Bamboo**  
  How do you onboard a new user and set permissions in Bamboo?

- **Onboarding New Users and Setting Permissions in Bitbucket**  
  How do you onboard a new user and set their permissions in Bitbucket?

## Kubernetes

- **Stateless Applications**  
  What are stateless applications, and how are they managed in Kubernetes?

- **How Will You Deploy Changes to Worker Nodes in Kubernetes?**  
  Provide a detailed step-by-step guide for deploying changes to worker nodes in Kubernetes.

- **How Services Interact with Each Other in Kubernetes**  
  Explain how services communicate with each other in a Kubernetes environment.

- **Communication Between Two AWS Clusters**  
  How do you ensure communication between two AWS Kubernetes clusters?

- **How to Backup an EKS Cluster**  
  What is the process for backing up an EKS cluster?

- **Rollout Strategies in EKS**  
  How does a rollout strategy work in EKS? Provide detailed steps.

- **Accessing S3 from EKS Cluster**  
  How can an application from your EKS cluster access an S3 bucket?

- **Using Secrets from AWS Secrets Manager in an EKS Cluster**  
  How can you use secrets from AWS Secrets Manager in an EKS cluster?

- **Node Affinity, Taints, and Tolerances**  
  Explain the concepts of node affinity, taints, and tolerances in Kubernetes.

- **Annotations in Kubernetes Manifest Files**  
  What are annotations in Kubernetes manifest files, and how are they used?

## Docker

- **CMD vs ENTRYPOINT in Dockerfile**  
  What is the difference between CMD and ENTRYPOINT in a Dockerfile?

- **Can We Have Multiple ENTRYPOINTs in a Dockerfile?**  
  What happens if you define multiple ENTRYPOINTs in a Dockerfile?

- **COPY vs ADD in Dockerfile**  
  What is the difference between COPY and ADD in a Dockerfile?

- **Save Command in Docker**  
  What is the `docker save` command, and how is it used?

- **How Do You Secure Your Docker Images?**  
  How do you secure your Docker images, and how do you verify that only signed images are deployed?

- **Init and Sidecar Containers in Docker**  
  What are init and sidecar containers, and how are they used in Docker?

- **Ephemeral Containers and Pods**  
  What are ephemeral containers, and how do they work in Kubernetes?

- **Layers in Docker Images**  
  Explain the concept of layers in Docker images and their importance.

## Contribute

Contributions are welcome! If you'd like to add more questions or provide explanations for the topics mentioned, feel free to fork the repo and submit a pull request.
