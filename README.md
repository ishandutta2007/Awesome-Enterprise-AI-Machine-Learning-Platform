# Awesome-Enterprise-AI-Machine-Learning-Platform

## Top Enterprise AI & Machine Learning Platform Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Enterprise MLOps, AutoML, Feature Stores & Model Serving*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise AI & Machine Learning Platforms**. These tools enable organizations to build, train, deploy, monitor, and govern machine learning models at scale, covering the full ML lifecycle from data preparation to production inference.



**Examples** include Adobe Sensei, Google Cloud AI Platform, AWS SageMaker, Microsoft Azure AI, DataRobot, H2O.ai, Dataiku, IBM watsonx, Clarifai, and C3 AI (the category leaders).



**Open-source emphasis**: This section is heavily expanded with active projects for self-hosted MLOps pipelines, AutoML frameworks, feature stores, model serving infrastructure, and end-to-end ML platforms — ideal for enterprises, data science teams, and developers building sovereign AI/ML infrastructure.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Adobe Sensei](https://business.adobe.com/products/sensei/sensei.html)**  

  Adobe's AI/ML platform embedded across Experience Cloud and Creative Cloud, providing intelligent features for content, personalization, and analytics.



- **[Google Cloud AI Platform](https://cloud.google.com/ai-platform)**  

  Unified platform for training, deploying, and managing ML models on Google Cloud, with Vertex AI as the current generation offering.



- **[AWS SageMaker](https://aws.amazon.com/sagemaker/)**  

  Fully managed ML service covering the entire workflow: data labeling, model building, training, tuning, deployment, and monitoring.



- **[Microsoft Azure AI](https://azure.microsoft.com/en-us/solutions/ai/)**  

  Comprehensive AI portfolio including Azure Machine Learning, Cognitive Services, and Azure OpenAI for enterprise ML workloads.



- **[DataRobot](https://www.datarobot.com/)**  

  Automated machine learning platform with AI governance, MLOps, and generative AI capabilities for enterprise data science teams.



- **[H2O.ai](https://h2o.ai/)**  

  AI platform offering automatic machine learning (Driverless AI), open-source ML libraries, and generative AI tools for enterprises.



- **[Dataiku](https://www.dataiku.com/)**  

  Centralized data science and ML platform enabling collaboration, AutoML, and production deployment across teams.



- **[IBM watsonx](https://www.ibm.com/watsonx)**  

  Enterprise AI and data platform with watsonx.ai (foundation models), watsonx.data (data store), and watsonx.governance (AI governance).



- **[Clarifai](https://www.clarifai.com/)**  

  Computer vision and multimodal AI platform with model orchestration, workflow automation, and enterprise deployment options.



- **[C3 AI](https://c3.ai/)**  

  Enterprise AI application platform with pre-built and custom AI applications for industries including manufacturing, energy, and defense.



## Open-Source GitHub Projects



- **[MLflow](https://github.com/mlflow/mlflow)**  

  Open-source platform for the ML lifecycle: experiment tracking, model registry, model packaging, and deployment; the de facto standard for ML experiment management.



- **[Kubeflow](https://github.com/kubeflow/kubeflow)**  

  Kubernetes-native ML toolkit for building portable ML workflows, including pipelines, training operators, and model serving.



- **[Feast](https://github.com/feast-dev/feast)**  

  The leading open-source feature store for ML, enabling feature definition, discovery, and serving across training and inference; 5,800+ stars, Apache-2.0 .



- **[Seldon Core](https://github.com/SeldonIO/seldon-core)**  

  MLOps framework for packaging, deploying, monitoring, and managing production ML models at scale on Kubernetes .



- **[AutoGluon](https://github.com/autogluon/autogluon)**  

  Fast and accurate AutoML library from AWS for tabular, image, text, and time-series data; "ML in 3 lines of code" .



- **[NNI (Neural Network Intelligence)](https://github.com/microsoft/nni)**  

  Microsoft's open-source AutoML toolkit for automating feature engineering, neural architecture search, model compression, and hyperparameter tuning; 14,000+ stars .



- **[LightAutoML](https://github.com/sb-ai-lab/LightAutoML)**  

  Fast and customizable AutoML framework from Sber AI Lab for automatic ML model creation on tabular data .



- **[TPOT](https://github.com/EpistasisLab/tpot)**  

  Python Automated Machine Learning tool that optimizes ML pipelines using genetic programming .



- **[MLJAR-Supervised](https://github.com/mljar/mljar-supervised)**  

  AutoML package for tabular data with feature engineering, hyperparameter tuning, explanations, and automatic documentation; 3,100+ stars .



- **[ClearML](https://github.com/clearml/clearml)**  

  Open-source MLOps platform for experiment management, data versioning, pipeline orchestration, and model serving; formerly Trains.



- **[LitServe](https://github.com/Lightning-AI/LitServe)**  

  Lightweight model serving engine from Lightning AI for deploying models, agents, and RAG pipelines with minimal configuration .



- **[KServe](https://github.com/kserve/kserve)**  

  Kubernetes-native model serving platform with standardized inference protocol, autoscaling, and support for multiple ML frameworks .



- **[Evidently](https://github.com/evidentlyai/evidently)**  

  Open-source ML observability framework for detecting data drift, model performance degradation, and data quality issues in production.



- **[Polyaxon](https://github.com/polyaxon/polyaxon)**  

  Platform for reproducible ML at scale, with experiment tracking, hyperparameter tuning, and Kubernetes-native orchestration .



- **[Pixeltable](https://github.com/pixeltable/pixeltable)**  

  AI data infrastructure providing a declarative, incremental approach for multimodal ML workloads and data pipelines .



- **[LaredoMLOps](https://github.com/laredo-mlops/laredo)**  

  Free MLOps tool for designing, training, storing, and deploying ML pipelines via a web interface, built on MLflow and KServe .



### Additional Strong Open-Source Options



- **DVC** — Data version control for ML projects, enabling reproducible pipelines and experiment tracking.

- **Metaflow** — Netflix's framework for building and managing data science workflows, with built-in versioning and orchestration .

- **Kedro** — Modular data science pipeline framework for creating reproducible, maintainable, and modular ML code .

- **Butterfree** — Tool for building feature stores with Spark-based pipelines .

- **ByteHub** — Simple, scalable feature store for ML .

- **DJL Serving** — Universal scalable model deployment solution from Deep Java Library .

- **MLflow** ecosystem tools — Integrations with Hugging Face, scikit-learn, PyTorch, and cloud platforms.

- **mindware** — Efficient AutoML system covering feature engineering, NAS, and hyperparameter tuning .



**Frameworks for building custom systems**: Combine **Kubeflow** or **Metaflow** for pipeline orchestration, **MLflow** for experiment tracking and model registry, **Feast** for feature management, **KServe** or **LitServe** for model serving, and **Evidently** for production monitoring in a fully self-hosted enterprise ML platform.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Enterprise AI/ML platforms must comply with applicable regulations and organizational policies (data privacy, model governance, AI ethics guidelines).

- Self-hosted open-source solutions require proper security hardening, infrastructure planning, and model lifecycle governance.

- Verify license terms for commercial use, especially for enterprise deployments.



---



**Made for enterprises, data science teams, ML engineers, and AI platform architects.**  

Let's make enterprise AI and machine learning more open, reproducible, and scalable.
