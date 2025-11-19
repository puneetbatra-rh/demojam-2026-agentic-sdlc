# Agentic AI SDLC 💻

This is to help you build Agentic AI system for automated SDLC that includes generation of user stories, code generation, test cases, security review and much more.
---

## 🚀 Setup & Installation Guide

Follow these steps to get the demo environment set up and running on your system.

### 1. Prerequisites

Before starting, ensure you have access to the necessary environment:

* Order the **demo environment** from the **Red Hat Demo Portal**.
https://catalog.demo.redhat.com/catalog?search=llama&item=babylon-catalog-prod%2Fsandboxes-gpte.llamastack-on-ocp.prod

* Once the environment is running, **open the Jupyter notebook** environment.

### 2. Repository Setup

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/puneetbatra-rh/demojam-2026-agentic-sdlc
    cd demojam-2026-agentic-sdlc
    ```

2.  **Configure Environment Variables:**
    * Rename the example environment file:
        ```bash
        mv .env.example .env
        ```
    * Open the newly renamed **`.env`** file and update the **model names**, **URL**, and **API key** to match the Large Language Models (LLMs) you have chosen and configured access for.

### 3. Environment Creation and Dependency Installation

1.  **Open a Terminal window** within your project directory.
2.  **Create a Virtual Environment:**
    ```bash
    python -m venv .venv
    ```
3.  **Activate the Virtual Environment:**
    ```bash
    source .venv/bin/activate
    ```
4.  **Install Required Packages:**
    ```bash
    pip install -r requirements.txt
    ```

### 4. Running the Application

Once all dependencies are installed, you can run the Streamlit application:

```bash
streamlit run app.py \
    --server.address=0.0.0.0 \
    --server.port=8501 \
    --server.enableCORS=false \
    --server.enableXsrfProtection=false
```

Application can now be accessed as per the below url

Append <Root URL of your Jupyter notebook until */lab> with */lab/proxy/8501/


