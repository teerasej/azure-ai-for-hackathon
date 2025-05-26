# Setup Instructions for Azure AI Hackathon

This guide provides detailed setup instructions to prepare your development environment for this Hackathon.

## Development Environment Setup

### 1. Visual Studio Code

Visual Studio Code is a lightweight but powerful source code editor that runs on your desktop.

1. Download and install Visual Studio Code from [https://code.visualstudio.com/](https://code.visualstudio.com/)
2. Follow the installation instructions for your operating system

#### Recommended VS Code Extensions

Install the following extensions to enhance your development experience:

1. **Python Extension**
   - Essential for Python development
   - Provides IntelliSense, linting, debugging, code navigation, and more
   - [Install Python Extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python)

#### Installing Extensions in VS Code

1. Open VS Code
2. Click on the Extensions view icon on the Sidebar (or press `Ctrl+Shift+X` / `Cmd+Shift+X`)
3. Search for the extension name
4. Click the Install button

### 2. Python Installation

Python is required for developing and running the AI applications in this hackathon.

1. Download and install Python from [https://www.python.org/downloads/](https://www.python.org/downloads/)
   - Ensure you install Python 3.8 or newer
   - On Windows, make sure to check the option "Add Python to PATH" during installation
2. Verify your installation by opening a terminal and running:
    ```bash
    python --version
    # or on some systems
    python3 --version
    ```

3. You should see output similar to:
    ```bash
    Python 3.10.12
    ```
    *(The version number may vary, but it should be 3.8 or newer.)*

#### Python Environment Setup

For best results, we recommend using a virtual environment:

1. Open terminal to this workspace, then run:

```bash
# Create a virtual environment
python -m venv .venv
```

2. Activate environment (Windows or MacOS)

**On Windows:**
```bash
.venv\Scripts\activate
```

**On macOS/Linux:**
```bash
source .venv/bin/activate
```

3.  Install the package

- A. Run the following command

```bash
# Install Semantic Kernel, Azure Document Intelligence, and Azure AI Foundry SDKs
pip install semantic-kernel azure-ai-documentintelligence azure-ai-projects azure-identity semantic-kernel
```

- B. Alternatively, install from requirements.txt file

```bash
# Install all required packages from requirements.txt
pip install -r requirements.txt
```


### Package Information

1. **Semantic Kernel**
   - Microsoft's AI orchestration library for integrating AI models
   - [Documentation](https://learn.microsoft.com/semantic-kernel/overview/)

2. **Azure AI Document Intelligence SDK**
   - SDK for working with Document Intelligence service
   - [Documentation](https://learn.microsoft.com/python/api/overview/azure/ai-document-intelligence-readme)

3. **Azure AI Foundry SDK**
    - SDK for building, deploying, and managing AI solutions on Azure
    - [Documentation](https://learn.microsoft.com/azure/ai-foundry/)


## Summary

After completing these setup steps, you'll have a fully configured development environment ready for the Azure AI Hackathon. You can now proceed to the specific topic guides to start exploring Azure AI services.

## Next Steps

Return to the [main README](./README.md) to explore the hackathon topics.
