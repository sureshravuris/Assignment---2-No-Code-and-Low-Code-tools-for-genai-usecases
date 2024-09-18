# Colab and LLM Demonstrations

This repository contains example Colabs demonstrating various tasks involving fine-tuning and training language models, running models locally, and showcasing key features of different platforms. The Colabs are structured to be executed in Google Colab with a focus on smaller, efficient models like Gemma 2B, using TPUs when necessary.

## Deliverables:

### a) LLama-Factory Demonstrations:
- **a.1) Supervised Fine-Tuning**: Demonstrate supervised fine-tuning using LoRA or QLoRA on LLaMA models.
- **a.2) DPO Training**: Demonstrate DPO (Direct Preference Optimization) training on LLaMA models.
- **a.3) PPO Training**: Demonstrate PPO (Proximal Policy Optimization) training on LLaMA models.

_Note_: Ensure that you authenticate with your Hugging Face token for accessing the LLaMA models.

### b) LM-Studio Features Demonstrations:
- **b.1) Gemma 2B**: Download and showcase the Gemma 2B model, including uploading PDFs and asking questions based on the content of the PDFs.

### c) Running LLMs Locally (Ollama):
- **c.1) Download Ollama and Gemma 2B**: Demonstrate running the Gemma 2B model on your local machine using Ollama.
- **c.2) Multimodal Demonstration with Ollama**: Showcase various multimodal capabilities with Ollama.
- **c.3) Ollama REST API**: Demonstrate the usage of Ollama's REST API with examples.
- **c.4) Ollama in Google Colab**: Run Ollama in Google Colab and demonstrate its features using this [guide](https://pub.towardsai.net/running-ollama-on-google-colab-free-tier-a-step-by-step-guide-9ef74b1f8f7a).
- **c.5) OpenWebUI Demonstration**: Use OpenWebUI to demonstrate various tasks with Ollama, highlighting key features of OpenWebUI.

### d) Dify.ai Workflow Capabilities:
- **d.1) Dify.ai Workflow**: Demonstrate the Dify.ai workflow capabilities including RAG engine, agent, workflow, observability, and local deployment. Dify.ai uses Ollama internally.

## Instructions:

1. Clone this repository and open the required Colab notebooks in Google Colab.
2. Ensure you use the smallest models possible (e.g., Gemma 2B quantized) to avoid resource limitations.
3. For each task, execute the Colab and verify that the code runs successfully in your environment.
4. Create video tutorials, explaining each Colab in approximately 1-minute walkthroughs. Show that the Colab is running in your environment, not just copied from GitHub.

## Notes:

- Ensure that the GitHub directory is neatly organized, with a clear `README.md` file.
- I will review some of the Colabs randomly during corrections to ensure everything works as expected.
