# An introduction to Kubeflow

## What is Kubeflow

Kubeflow is the foundation of tools for AI Platforms on Kubernetes.

AI platform teams can build on top of Kubeflow by using each project independently or deploying the entire AI reference platform to meet their specific needs. The Kubeflow AI reference platform is composable, modular, portable, and scalable, backed by an ecosystem of Kubernetes-native projects that cover every stage of the AI lifecycle.

Whether you’re an AI practitioner, a platform administrator, or a team of developers, Kubeflow offers modular, scalable, and extensible tools to support your AI use cases.

## What are Kubeflow Projects:

Kubeflow is composed of multiple open source projects that address different aspects of the AI lifecycle. These projects are designed to be usable both independently and as part of the Kubeflow AI reference platform. This provides flexibility for users who may not need the full end-to-end AI platform capabilities but want to leverage specific functionalities, such as model training or model serving.

        Kubeflow Project	Source Code
        Kubeflow KServe	kserve/kserve
        Kubeflow Katib	kubeflow/katib
        Kubeflow Model Registry	kubeflow/model-registry
        Kubeflow Notebooks	kubeflow/notebooks
        Kubeflow Pipelines	kubeflow/pipelines
        Kubeflow Spark Operator	kubeflow/spark-operator
        Kubeflow Trainer	kubeflow/trainer

        
## What is the Kubeflow AI Reference Platform
The Kubeflow AI reference platform refers to the full suite of Kubeflow projects bundled together with additional integration and management tools. Kubeflow AI reference platform deploys the comprehensive toolkit for the entire AI lifecycle. The Kubeflow AI reference platform can be installed via Packaged Distributions or Kubeflow Manifests.

Kubeflow AI Reference Platform Tool	Source Code
Central Dashboard	kubeflow/dashboard
Profile Controller	kubeflow/dashboard
Kubeflow Manifests	kubeflow/manifests


## Kubeflow Overview Diagram:

The following diagram shows the Kubeflow projects to cover each stage of the AI lifecycle on top of Kubernetes. 
Read the architecture overview to learn how Kubeflow projects fit in AI lifecycle.


Kubeflow Overview Diagram:

<img width="1677" height="1202" alt="image" src="https://github.com/user-attachments/assets/43d24c96-59b6-4a83-9577-7373a4be3916" />





**Reference Link:** https://www.kubeflow.org/docs/started/introduction/

## Kubeflow VS MLflow


Kubeflow (Google-native) and MLflow (Databricks-originated) are distinct MLOps tools often used together rather than as direct replacements.
Kubeflow is a heavy-duty, Kubernetes-native platform for orchestrating end-to-end, scalable production ML pipelines. 
MLflow is a lightweight, infrastructure-agnostic framework focused on experiment tracking, model registry, and packaging.



## Kubeflow Components:

<img width="549" height="574" alt="Screenshot 2026-03-05 at 10 57 25 AM" src="https://github.com/user-attachments/assets/a4f0b0fa-eb5a-49d3-8351-dbea3d4465ec" />

=============================================================================

<img width="1297" height="671" alt="Screenshot 2026-03-05 at 10 55 59 AM" src="https://github.com/user-attachments/assets/bf1edfea-9b46-4f7c-9147-09c58cdcdb51" />

=============================================================================

<img width="1288" height="615" alt="Screenshot 2026-03-05 at 11 01 04 AM" src="https://github.com/user-attachments/assets/03b49968-0442-4c4e-9075-2b0c0f1e4fbc" />

=============================================================================

<img width="1286" height="697" alt="Screenshot 2026-03-05 at 10 57 00 AM" src="https://github.com/user-attachments/assets/49cd87af-b237-4ae7-8ba0-368d7aff7936" />

=============================================================================
<img width="1314" height="685" alt="Screenshot 2026-03-05 at 11 18 29 AM" src="https://github.com/user-attachments/assets/b996ebad-3ca9-4a83-b313-431d38869630" />

=============================================================================

<img width="1430" height="636" alt="Screenshot 2026-03-05 at 11 24 08 AM" src="https://github.com/user-attachments/assets/3e812396-0a1e-4fb2-8f2d-469c9e753308" />

=============================================================================
<img width="1312" height="659" alt="Screenshot 2026-03-05 at 11 29 33 AM" src="https://github.com/user-attachments/assets/09787211-1cab-4f75-aeef-b5ce9b8cc17e" />

=============================================================================
<img width="1377" height="626" alt="Screenshot 2026-03-05 at 11 34 09 AM" src="https://github.com/user-attachments/assets/59d21953-2bde-48f7-bdf8-983b2dc19b43" />

=============================================================================
<img width="1336" height="586" alt="Screenshot 2026-03-05 at 11 35 51 AM" src="https://github.com/user-attachments/assets/2aa1dd3b-3f07-4c86-ad85-1ffe6f49fc17" />

=============================================================================
<img width="1339" height="558" alt="Screenshot 2026-03-05 at 11 39 36 AM" src="https://github.com/user-attachments/assets/ef5dea0f-d13e-4e38-b1f4-e43dfe3c0e09" />

=============================================================================

<img width="1065" height="446" alt="Screenshot 2026-03-05 at 11 48 24 AM" src="https://github.com/user-attachments/assets/f1bdee6f-3e1f-4a69-92c4-d3239c268cb7" />

=============================================================================

🚀Getting Started with Kubeflow v1.6.1 | Install & Setup Overview

Kubeflow is one of the most powerful platforms for building and managing machine learning workflows on Kubernetes. In this video, we’ll walk you through the installation and setup process for Kubeflow v1.6.1, covering everything you need to know to get up and running — from prerequisites to deployment. Whether you're new to Kubeflow or upgrading to the latest version, this overview will help you start strong.

---

📚 What You'll Learn in This MLOps Course:

✅ MLOps concepts from beginner to advanced  
✅ ML experiment tracking & version control using MLflow  
✅ CI/CD pipelines using GitHub Actions for ML models  
✅ Containerization of ML applications using Docker  
✅ Model deployment on Kubernetes with real-world use cases  
✅ Introduction to Kubeflow and building Kubeflow Pipelines  
✅ Model monitoring, security, logging, and versioning  
✅ Scalable production-ready model serving  
✅ A full end-to-end deployment case study

=============================================================================
<img width="1197" height="556" alt="Screenshot 2026-03-05 at 11 53 06 AM" src="https://github.com/user-attachments/assets/0c483e34-113b-4345-85de-67aedd902abd" />

=============================================================================
<img width="1179" height="629" alt="Screenshot 2026-03-05 at 11 53 31 AM" src="https://github.com/user-attachments/assets/52167fc6-6221-47dd-9a8c-d86edb283250" />

=============================================================================
<img width="1011" height="493" alt="Screenshot 2026-03-05 at 11 58 20 AM" src="https://github.com/user-attachments/assets/25b7226a-2871-472c-a63b-2f1c63f43908" />


=============================================================================
<img width="1308" height="635" alt="Screenshot 2026-03-05 at 12 18 46 PM" src="https://github.com/user-attachments/assets/2e22432a-b265-4aed-9d34-7f2625a7d0e0" />

=============================================================================
Description: 

we dive deep into the world of Kubeflow Pipelines and show you how to deploy a complete Machine Learning workflow locally using Docker and Minikube. Whether you're a data scientist, ML engineer, or just curious about MLOps, this tutorial will guide you step-by-step through the process of:

**1. Loading Data:** Learn how to efficiently load your dataset into the pipeline.

**2. Preprocessing Data:** Discover best practices for cleaning and transforming your data.

**3. Training a Machine Learning Model:** Train your model using Kubeflow's powerful orchestration capabilities.

**4. Evaluating the Model:** Evaluate your model's performance and ensure it meets your expectations.


**Tools & Technologies Used:**

1. **Kubeflow Pipelines:** For orchestrating the ML workflow.
   
3. **Docker:** For containerizing your pipeline components.
   
5. **Minikube:** For running a local Kubernetes cluster.

**Timestamps:**

                Introduction: 
                Code Overview
                Setting Up Docker Minikube & Kubectl
                Setting Up Python venv
                Setting Up Kubeflow environment
                Build and Deploy Kubeflow Pipeline
                Create & Run Pipeline in Kubeflow UI
                Clean Up

Now you'll have a fully functional Kubeflow Pipeline running on your local machine, ready to handle your ML projects with ease.
=============================================================================

=============================================================================




