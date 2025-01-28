# deepseek-on-sagemaker
This notebook is meant to run in an appropriately permissioned SageMaker Studio environment with network access to HuggingFace model repositories and the permissions to stand up model endpoints.

The first demo describes how to deploy **DeepSeek-R1-Distill-Llama-8B** on an ml.g5.2xlarge instance. Ensure your Service Quota for ml.g5.2xlarge is at least 1.

The second demo describes how to deploy **DeepSeek-R1-Distill-Llama-70B** on an ml.inf2.48xlarge instance. Ensure your Service Quota for ml.inf2.48xlarge is at least 1.

These instructions were pulled straight from HuggingFace's instructions to deploy DeepSeek models onto AWS. Virtually none of this code is my original work; it is compiled here for ease of access for personal use. Check the HuggingFace pages on DeepSeek for more information, links included below for convenience.

[DeepSeek-R1-Distill-Llama-8B](https://huggingface.co/deepseek-ai/DeepSeek-R1-Distill-Llama-8B)

[DeepSeek-R1-Distill-Llama-70B](https://huggingface.co/deepseek-ai/DeepSeek-R1-Distill-Llama-70B)
