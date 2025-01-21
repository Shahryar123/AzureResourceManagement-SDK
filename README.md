"# AzureResourceManagement-SDK" 

To fetch Azure resource details using the Azure SDK, you can use the ResourceManagementClient from the @azure/arm-resources package. This is the complete code example for getting resource details in a Node.js application.



# AzureResourceManagement-SDK

Effortlessly fetch and manage Azure resource details using the Azure SDK for Node.js! This project demonstrates how to utilize the `ResourceManagementClient` from the `@azure/arm-resources` package to interact with Azure resources in your subscription.

## 🌟 Features
- Fetch all resources in your Azure subscription.
- List resource details including name, type, location, and ID.
- Built with Node.js and the Azure SDK for easy integration into your cloud workflows.

## 📋 Prerequisites
- An active Azure subscription.
- Azure CLI installed. Download Azure CLI.

Install Azure SDK dependencies:
    - npm install @azure/identity @azure/arm-resources
Set up Azure authentication:
    - az login

## 🚀 Quick Start

### 1. **Clone the Repository**
```bash
git clone https://github.com/<your-username>/AzureResourceManagement-SDK.git
cd AzureResourceManagement-SDK
