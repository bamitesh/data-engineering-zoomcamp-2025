# Module 1: Docker and Terraform

Welcome to the first module of the Data Engineering Zoomcamp 2025! This module focuses on two essential tools for modern data engineering: Docker and Terraform. We'll be covering their application in the context of Google Cloud Platform (GCP) and SQL databases.

## Table of Contents

1. [Introduction](#introduction)
2. [Terraform with GCP](#terraform-with-gcp)
3. [Docker with SQL](#docker-with-sql)
4. [Prerequisites](#prerequisites)
5. [Setup](#setup)
6. [Exercises](#exercises)
7. [Additional Resources](#additional-resources)

## Introduction

In this module, you'll learn how to use Terraform for infrastructure as code (IaC) with Google Cloud Platform, and how to containerize SQL databases using Docker. These skills are fundamental for setting up scalable and reproducible data engineering environments.

## Terraform with GCP

In this section, we'll cover:

- Introduction to Infrastructure as Code (IaC)
- Basics of Terraform
- Setting up a GCP project
- Writing Terraform configurations for GCP resources
- Managing state with Terraform
- Best practices for using Terraform in data engineering projects

### Key Concepts

- Terraform providers and resources
- GCP service accounts and authentication
- Managing compute instances, storage buckets, and networking with Terraform

## Docker with SQL

This section includes:

- Introduction to containerization with Docker
- Dockerizing SQL databases (PostgreSQL/MySQL)
- Writing Dockerfiles for data applications
- Docker networking and volume management
- Docker Compose for multi-container applications

### Key Concepts

- Docker images and containers
- Persistent storage with Docker volumes
- Connecting to SQL databases in Docker containers
- Docker Compose for local development environments

## Prerequisites

Before starting this module, ensure you have:

- A Google Cloud Platform account
- Basic understanding of cloud computing concepts
- Familiarity with SQL databases
- Basic command-line skills

## Setup

1. Install Terraform:
   ```bash
   # For macOS using Homebrew
   brew install terraform

   # For Windows using Chocolatey
   choco install terraform
   ```

2. Install Docker:
   Visit the [official Docker website](https://docs.docker.com/get-docker/) and follow the installation instructions for your operating system.

3. Set up Google Cloud SDK:
   Follow the [official documentation](https://cloud.google.com/sdk/docs/install) to install and configure the Google Cloud SDK.

## Exercises

1. Terraform with GCP:
   - Create a Terraform configuration to set up a GCP project
   - Use Terraform to create a Cloud Storage bucket
   - Deploy a simple compute instance using Terraform

2. Docker with SQL:
   - Create a Dockerfile for a PostgreSQL database
   - Build and run the Docker container
   - Connect to the database and perform basic SQL operations
   - Create a Docker Compose file to set up a multi-container environment with a database and a simple application

## Additional Resources

- [Terraform Documentation](https://www.terraform.io/docs/index.html)
- [Google Cloud Terraform Provider](https://registry.terraform.io/providers/hashicorp/google/latest/docs)
- [Docker Documentation](https://docs.docker.com/)
- [PostgreSQL Docker Official Image](https://hub.docker.com/_/postgres)

---

Happy learning! If you have any questions or run into issues, please don't hesitate to ask for help in the course forum or during live sessions.
```

This README provides a comprehensive overview of the "01-docker-terraform" module, covering both the Terraform with GCP and Docker with SQL sub-modules. It includes:

1. An introduction to the module
2. Detailed sections for each sub-module
3. Key concepts covered in each sub-module
4. Prerequisites for the module
5. Setup instructions for necessary tools
6. Exercise suggestions for hands-on practice
7. Additional resources for further learning
