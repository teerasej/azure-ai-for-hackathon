# Creating an Azure Web App Service

This guide will walk you through creating an Azure Web App Service with a sample web application using the Azure Portal. We'll keep it simple and straightforward.

## Prerequisites

- An Azure account with an active subscription
- Access to the Azure Portal ([portal.azure.com](https://portal.azure.com))

## Step 1: Sign in to Azure Portal

1. Open your web browser and navigate to [portal.azure.com](https://portal.azure.com)
2. Sign in with your Azure account credentials
3. You should see the Azure Portal dashboard

## Step 2: Create a New Web App

1. **Click "Create a resource"** in the top-left corner of the Azure Portal
2. **Search for "Web App"** in the search box
3. **Select "Web App"** from the results
4. **Click "Create"** to start the configuration process

## Step 3: Configure Basic Settings

Fill out the **Basics** tab with the following information:

### Project Details
- **Subscription**: Select your Azure subscription
- **Resource Group**: 
  - Click "Create new" if you don't have one
  - Enter a name like `rg-webapp-demo`
  - Click "OK"

### Instance Details
- **Name**: Enter a unique name for your web app (e.g., `my-demo-webapp-2025`)
  - ⚠️ **Note**: This name must be globally unique across all Azure web apps
- **Publish**: Select **Code**
- **Runtime stack**: Choose **Node.js 20 LTS** (recommended for beginners)
- **Operating System**: Select **Linux**
- **Region**: Choose a region close to you (e.g., East US, West Europe)

### Pricing Plans
- **Linux Plan**: Click "Create new"
  - Enter a name like `asp-webapp-demo`
  - Click "OK"
- **Pricing tier**: Click "Explore pricing options"
  - Select **Free F1** (perfect for testing)
  - Click "Select"

## Step 4: Skip Additional Configurations (For Simplicity)

1. **Click "Review + create"** to skip the optional tabs
   - We're keeping this simple, so we'll use default settings for:
     - Deployment
     - Networking
     - Monitoring
     - Tags

## Step 5: Review and Create

1. **Review your configuration** on the summary page
2. **Click "Create"** to deploy your web app
3. **Wait for deployment** (usually takes 1-2 minutes)
4. Once complete, click **"Go to resource"**

## Step 6: Access Your Web App

1. **Go back to your Web App resource** in the Azure Portal
2. **Click on "Browse"** at the top of the page, or
3. **Copy the URL** shown in the Overview section (it looks like: `https://your-app-name.azurewebsites.net`)
4. **Open the URL** in a new browser tab

You should now see your sample web application running live on Azure! 🎉

## Step 7: Managing Your Web App

### View Application Logs
1. Go to **Monitoring** > **Log stream**
2. This shows real-time logs from your application

### Monitor Performance
1. Go to **Monitoring** > **Metrics**
2. You can see CPU usage, memory usage, and request counts

### Scale Your App (If needed)
1. Go to **Settings** > **Scale up (App Service plan)**
2. Choose a higher tier for more resources

## Troubleshooting

### Common Issues:

1. **App name already exists**: Choose a different, globally unique name
2. **Page not loading**: Wait a few minutes for deployment to complete
3. **Default page showing**: Make sure your `index.html` is in the root directory

### Getting Help:
- Check the **Activity log** in your resource for any deployment errors
- Use **Diagnose and solve problems** for automated troubleshooting

## Clean Up Resources (Optional)

To avoid charges:
1. Go to your **Resource Group** (`rg-webapp-demo`)
2. Click **"Delete resource group"**
3. Type the resource group name to confirm
4. Click **"Delete"**

---

## 🎯 Summary

You've successfully:
- ✅ Created an Azure Web App Service
- ✅ Deployed a sample web application
- ✅ Accessed your live web app on the internet
- ✅ Learned basic management tasks

Your web app is now live and accessible worldwide! You can continue building on this foundation by adding more features, connecting databases, or implementing automated deployments.

## Next Steps

- Explore [Azure App Service documentation](https://docs.microsoft.com/en-us/azure/app-service/)
- Learn about [Deployment options](https://docs.microsoft.com/en-us/azure/app-service/deploy-continuous-deployment)
- Check out [Monitoring and diagnostics](https://docs.microsoft.com/en-us/azure/app-service/troubleshoot-diagnostic-logs)
