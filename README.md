# 🚀 AI KubeWatch

AI KubeWatch is an AI-driven auto-scaling solution using Azure Functions and Azure Kubernetes Service (AKS) to dynamically adjust resources based on real-time application performance metrics. 📈

## 📋 Table of Contents

- [Features](#-features)
- [Getting Started](#-getting-started)
- [Documentation](#-documentation)
- [Deployment](#-deployment)
- [Configuration](#-configuration)
- [Contributing](#-contributing)
- [License](#-license)

## 🎉 Features

- AI-powered auto-scaling of AKS clusters based on real-time performance metrics.
- Easily configurable scaling rules to handle varying workloads efficiently.
- Integrates with Azure Functions to enable dynamic resource adjustments.
- Includes machine learning model for demand forecasting.

## 🚀 Getting Started

To get started with AI KubeWatch, follow these steps:

1. Clone the repository: `https://github.com/praveenthopalle/AI_KubeWatch.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Configure the settings in `config/config.yaml` and `config/scaling_rules.yaml`.
4. Deploy the application to AKS using the provided scripts: `./scripts/deploy_to_aks.sh`
5. Monitor the auto-scaling behavior through Azure Functions and AKS dashboard.

## 📖 Documentation

For detailed information on the architecture, deployment, and usage of AI KubeWatch, check out the [Documentation](docs) folder:

- [Architecture](docs/architecture.md): Overview of the solution's design and components.
- [Deployment](docs/deployment.md): Step-by-step guide on deploying the application to AKS.
- [User Guide](docs/user_guide.md): Instructions on configuring and using the auto-scaling solution.

## 🚀 Deployment

The AI KubeWatch solution can be deployed to Azure Kubernetes Service (AKS) using the provided deployment script:

```bash
./scripts/deploy_to_aks.sh
```
---

Make sure you have the necessary permissions and the AKS cluster is properly set up before running the script.

## 🔧 Configuration
AI KubeWatch provides configuration options through YAML files in the config directory:

- `config.yaml`: General settings for the application.
- `scaling_rules.yaml`: Rules for auto-scaling based on performance metrics.

## 👥 Contributing
Contributions to AI KubeWatch are welcome! To contribute, please follow our Contribution Guidelines.

## 📄 License
This project is licensed under the [MIT License](LICENSE).
