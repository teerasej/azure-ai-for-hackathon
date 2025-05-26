# Creating an Azure AI Foundry Project

This guide walks you through creating an Azure AI Foundry project and exploring the extensive model catalog available to AI developers.

## What is Azure AI Foundry?

Azure AI Foundry is a service that helps developers discover, evaluate, customize, and deploy AI models from various providers. It provides a unified experience for working with models from Microsoft and other leading AI companies.

## Prerequisites

- An Azure account with an active subscription
- Permission to create resources in your Azure subscription
- Basic understanding of AI concepts

## Step-by-Step Instructions

### 1. Access Azure AI Foundry

1. Open your web browser and navigate to [https://ai.azure.com](https://ai.azure.com)
2. Sign in with your Azure account credentials
3. If this is your first time, you may need to complete some initial setup steps

### 2. Create a New Project

1. From the AI Foundry homepage, click on **Projects** in the left navigation
2. Click **Create new project**
3. Fill in the project details:
   - **Project name**: Enter a descriptive name for your project
   - **Description** (optional): Add details about your project's purpose
   - **Subscription**: Select your Azure subscription
   - **Resource group**: Select an existing resource group or create a new one
   - **Region**: Choose a region for your project resources
4. Click **Create project**

### 3. Explore the Model Catalog

1. In your new project, click on **Models** in the left navigation
2. Click **Add model** to explore the model catalog
3. Browse through different model categories:
   - **Text**: Models for text generation, summarization, translation, etc.
   - **Vision**: Models for image analysis, object detection, etc.
   - **Multimodal**: Models that work with multiple types of data
   - **Audio**: Models for speech recognition, text-to-speech, etc.

### 4. Compare Models

1. From the model catalog, select multiple models that interest you
2. Click **Compare** to see models side-by-side
3. Review the comparison across important dimensions:
   - **Model capabilities**: Compare specific features and functionalities
   - **Performance metrics**: Analyze benchmark results and accuracy ratings
   - **Latency and throughput**: Compare processing speeds and capacity
   - **Responsible AI considerations**: Review ethical considerations for each model
   - **Pricing and quotas**: Compare costs and usage limitations
4. Use the comparison data to select the most suitable model for your project needs

### 5. Add a Model to Your Project

1. Once you've found a model you want to work with, click **Add to project**
2. Select your project from the dropdown if prompted
3. Configure any model-specific settings
4. Click **Add** to add the model to your project

### 6. Deploy a Model (Optional)

1. In your project, go to the **Models** section
2. Find the model you added and click on it
3. Click **Deploy**
4. Configure the deployment settings:
   - **Deployment name**: Give your deployment a name
   - **Scale settings**: Choose appropriate compute resources
   - **Advanced settings**: Configure additional options as needed
5. Click **Deploy** to start the deployment process

### 7. Test the Deployed Model (Optional)

1. Once deployment is complete, go to the **Deployments** section
2. Select your deployment
3. Click on the **Test** tab
4. Enter test inputs based on the model type
5. Click **Run** to see the model's output

## Summary

Congratulations! You have successfully:
- Created an Azure AI Foundry project
- Explored the diverse model catalog
- Added models to your project
- Learned how to deploy and test models (optional)

Azure AI Foundry provides a centralized environment for exploring and deploying state-of-the-art AI models, making it easier to incorporate advanced AI capabilities into your hackathon projects.

## Cleaning Up Resources

When you're finished with this hackathon, you should delete the resources to avoid incurring costs:

1. Sign in to the [Azure Portal](https://portal.azure.com)
2. Navigate to Resource Groups
3. Select the resource group containing your AI Foundry resources
4. Click **Delete resource group**
5. Type the resource group name to confirm deletion
6. Click **Delete**

This will delete all resources in the resource group, including your AI Foundry project and any deployed models.

## Next Steps

- Explore the [Azure AI Foundry documentation](https://learn.microsoft.com/azure/ai-studio/) for more detailed information
- Consider integrating AI models with other Azure services for your hackathon project
- Check out [Azure AI samples and tutorials](https://learn.microsoft.com/azure/ai-services/tutorials/) for inspiration
