# Setting Up Azure AI Document Intelligence Service

This guide walks you through creating an Azure AI Document Intelligence service (formerly known as Form Recognizer) using the free tier in the Azure Portal.

## What is Azure AI Document Intelligence?

Azure AI Document Intelligence is a cloud-based service that uses machine learning to extract text, key-value pairs, tables, and structure from documents. It can process various document types including invoices, receipts, IDs, forms, and more.

## Prerequisites

- An Azure account with an active subscription
- Permission to create resources in your Azure subscription

## Step-by-Step Instructions

### 1. Sign in to the Azure Portal

1. Open your web browser and navigate to [https://portal.azure.com](https://portal.azure.com)
2. Sign in with your Azure account credentials

### 2. Create a Document Intelligence Resource

1. Click on **Create a resource** in the upper left corner of the Azure portal
2. Search for **Document Intelligence** in the search bar
3. Select **Document Intelligence** from the results
4. Click the **Create** button

### 3. Configure Basic Settings

1. **Subscription**: Select your Azure subscription
2. **Resource group**: Create a new resource group or select an existing one
   - To create a new one, click **Create new** and give it a name like `ai-hackathon-rg`
3. **Region**: Select a region close to your location
4. **Name**: Enter a unique name for your Document Intelligence resource
5. **Pricing tier**: Select **Free F0** (0 USD/month) for this hackathon

### 4. Review and Create

1. Click the **Review + create** button
2. Review all the settings you've configured
3. Click **Create** to deploy the resource

### 5. Access Your Resource

1. Wait for the deployment to complete (this usually takes less than a minute)
2. Once deployment is complete, click **Go to resource**
3. On the resource overview page, note the following important information:
   - **Endpoint**: The URL you'll use to connect to your Document Intelligence service
   - **Keys**: The keys used to authenticate your requests (found under "Keys and Endpoint" in the left menu)

## Summary

Congratulations! You have successfully:
- Created an Azure AI Document Intelligence resource using the free tier
- Located the service endpoint and authentication keys

You can now use this service to extract information from various documents. The next guide will show you how to use Document Intelligence Studio to test your new service.

## Next Steps

- Proceed to [Using Document Intelligence Studio](./doc-intelligence-studio.md) to start analyzing documents
- Explore the [Document Intelligence documentation](https://learn.microsoft.com/azure/ai-services/document-intelligence/) for more details
