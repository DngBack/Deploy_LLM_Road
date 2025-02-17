# vLLM Supported Features

## 1. Support for Large Language Models (LLM)

- **Third-party models:** vLLM supports various large language models from different sources, allowing community contributions and model expansion.  
  [Source](https://docs.vllm.ai/en/v0.6.5/models/supported_models.html?utm_source=chatgpt.com)
- **Compatibility check:** Users can verify if a model is supported by checking the `config.json` file in the Hugging Face repository. If the `"architectures"` field contains a model architecture listed in vLLM’s documentation, the model is supported.  
  [Source](https://docs.vllm.ai/en/v0.6.5/models/supported_models.html?utm_source=chatgpt.com)

## 2. Integration with LoRA Adapters

- **Dynamic loading and unloading:** The vLLM server supports dynamically loading and removing LoRA adapters through dedicated API endpoints, providing flexibility in model adaptation.  
  [Source](https://www.studywithgpt.com/vi/tutorial/p3w612?utm_source=chatgpt.com)

## 3. OpenAI API Compatibility

- **Deploying a compatible server:** vLLM can be deployed as an OpenAI API-compatible server, enabling seamless integration with existing applications without requiring structural changes.  
  [Source](https://docs.vllm.ai/en/stable/design/arch_overview.html?utm_source=chatgpt.com)

## 4. Cloud Deployment Support

- **Google Cloud Run with GPU:** vLLM can be deployed on cloud services like Google Cloud Run, leveraging GPU support to enhance inference performance.  
  [Source](https://codelabs.developers.google.com/codelabs/how-to-run-inference-cloud-run-gpu-vllm?hl=vi&utm_source=chatgpt.com)

With these extensive features and support, vLLM serves as a flexible and efficient solution for deploying and serving large language models in various applications.
