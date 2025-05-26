# Using Document Intelligence Studio

This guide demonstrates how to use Document Intelligence Studio to test the capabilities of your Azure AI Document Intelligence service.

## What is Document Intelligence Studio?

Document Intelligence Studio is a web-based interface that allows you to test and experiment with the Document Intelligence service without writing code. It provides a user-friendly way to analyze documents, train custom models, and visualize results.

## Prerequisites

- An Azure AI Document Intelligence resource (created in the [previous guide](./doc-intelligence-setup.md))
- Sample documents to analyze (PDFs, images, or other supported formats)

## Step-by-Step Instructions

### 1. Access Document Intelligence Studio

1. Open your web browser and navigate to [https://documentintelligence.ai.azure.com/studio](https://documentintelligence.ai.azure.com/studio)
2. Sign in with the same account you used to create your Azure resource
3. If prompted, select your Azure subscription and the Document Intelligence resource you created earlier

### 2. Testing the Receipt Prebuilt Model

The Receipt model is specifically designed to extract key information from receipts such as merchant details, transaction amounts, tax information, line items, and more.

1. From the studio homepage, click on the **Prebuilt models** tab
2. Locate and click on the **Receipt** model
3. Click **Try it out** to begin testing

### 3. Analyzing Receipts

1. Prepare a receipt document for analysis:
   - You can use a photo or scan of a receipt
   - Supported formats include JPG, PNG, PDF, and TIFF
   - For best results, ensure the receipt is clearly visible and not blurry

2. Upload your receipt by either:
   - Clicking **Browse for a file** and selecting your receipt document
   - Dragging and dropping the file into the designated area

3. Wait for the analysis to complete (typically just a few seconds)

### 4. Exploring Receipt Analysis Results

Once the analysis is complete, you'll see detailed information extracted from your receipt:

1. **Document View**: On the left side, you'll see your original receipt with highlighted regions
   
2. **Extracted Data**: On the right side, explore the structured data extracted from your receipt:
   - **Merchant Information**: Name, address, phone number
   - **Transaction Details**: Date, time, total amount
   - **Payment Information**: Payment method, card details (partially masked)
   - **Tax Information**: Tax amounts and rates
   - **Line Items**: Individual items purchased with prices
   - **Custom Fields**: Additional receipt-specific information

3. **JSON View**: Click the "JSON" tab to see the raw data structure that would be returned by the API

4. **Confidence Scores**: Notice the confidence scores for each extracted field, indicating how certain the model is about each piece of information



## Summary

Congratulations! You have successfully:
- Accessed Document Intelligence Studio
- Tested the Receipt prebuilt model with your own receipts
- Explored the detailed information extraction capabilities
- Learned how to interpret the analysis results

Document Intelligence Studio's Receipt model provides a powerful, code-free way to experiment with receipt processing capabilities before integrating them into your applications.

## Cleaning Up Resources

When you're finished with this hackathon, you should delete the resources to avoid incurring costs:

1. Sign in to the [Azure Portal](https://portal.azure.com)
2. Navigate to Resource Groups
3. Select the resource group containing your Document Intelligence resource
4. Click **Delete resource group**
5. Type the resource group name to confirm deletion
6. Click **Delete**

This will delete all resources in the resource group, including your Document Intelligence service.

## Next Steps

- Proceed to [Creating an Azure AI Foundry Project](./ai-foundry-project.md)
- Explore the [Document Intelligence API documentation](https://learn.microsoft.com/rest/api/aiservices/document-intelligence/) to learn about programmatic integration
