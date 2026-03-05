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

<img width="1677" height="1202" alt="image" src="https://github.com/user-attachments/assets/43d24c96-59b6-4a83-9577-7373a4be3916" />


Kubeflow Overview Diagram
**Reference Link:** https://www.kubeflow.org/docs/started/introduction/

## Kubeflow VS MLflow


Kubeflow (Google-native) and MLflow (Databricks-originated) are distinct MLOps tools often used together rather than as direct replacements. Kubeflow is a heavy-duty, Kubernetes-native platform for orchestrating end-to-end, scalable production ML pipelines. MLflow is a lightweight, infrastructure-agnostic framework focused on experiment tracking, model registry, and packaging
