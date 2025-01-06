<div align="center">
  <img src="./static/knekig.png" alt="Kineki" width="60%" />
</div>
</p>
<h3 align="center">
    Next Generation Agent Deployment Tool
</h3>

[<img width="220" alt="Download button" src="https://github.com/user-attachments/assets/a5d51b8b-b30a-4a16-a902-ab6ef1d58dc0">](https://github.com/KILNAI/KILN/releases/tag/v.0.1.0)

## Key Features

- 🚀 **Effortless Agent Deployment**: Launch custom-trained AI agents with absolutely no coding required.
- 🎛️ **Cross-Platform Compatibility**: Enjoy a seamless experience with our custom-built app available for Windows, macOS, and Linux.
- 🪙 **Token Integration**: Leverage your own token to power and sustain your agents ecosystem.
- 🤝 **Free to Use App**: Our application is free to use. Note: Deploying agents online will require $KINEKI tokens. Hosting them locally will remain free.
- 📝 **Auto-Prompts**: Generate a variety of prompts from your data, including chain-of-thought, few-shot, and multi-shot.
- 🌐 **Interactive Training Data Generation**: Create robust training datasets with our intuitive and interactive visual tooling.
- 🧑‍💻 **Open-Source Library and API**: Our Python library and OpenAPI REST API are MIT open source.
- 🔒 **Privacy-First**: We can't see your data. Bring your own API keys or run locally with Ollama.
- 🤖 **Synthetic Data Generation**: Generate training data with our interactive visual tooling.
- 🎛️ **Fine Tuning**: Zero-code fine-tuning for Llama, GPT4o, and Mixtral. Automatic serverless deployment of models.

## Demo

In this demo, I create 9 fine-tuned models (including Llama 3.x, Mixtral, and GPT-4o-mini) in just 18 minutes, achieving great results for less than $6 total cost. [See details](guides/Fine%20Tuning%20LLM%20Models%20Guide.md).

<a href="guides/Fine%20Tuning%20LLM%20Models%20Guide.md">
<img alt="Kineki Preview" src="https://github.com/user-attachments/assets/51db632b-be98-4fc6-a31c-0ba6fd54dcbb">
</a>

## Download Kineki Desktop Apps

The Kineki desktop app is completely free. Available on MacOS, Windows and Linux.

[<img width="220" alt="Download button" src="https://github.com/user-attachments/assets/a5d51b8b-b30a-4a16-a902-ab6ef1d58dc0">](https://github.com/KILNAI/KILN/releases/tag/v.0.1.0)

## Install Python Library

[![PyPI - Version](https://img.shields.io/pypi/v/kiln-ai.svg?logo=pypi&label=PyPI&logoColor=gold)](https://pypi.org/project/kiln-ai/) [![Docs](https://img.shields.io/badge/docs-pdoc-blue)](https://kiln-ai.github.io/Kiln/kiln_core_docs/index.html)

Our open-source [python library](https://pypi.org/project/kiln-ai/) allows you to integrate Kineki datasets into your own workflows, build fine tunes, use Kineki in Notebooks, build custom tools, and much more! [Read the docs](https://kiln-ai.github.io/Kiln/kiln_core_docs/index.html).

```bash
pip install kineki-ai
```

## Learn More

### Build High Quality AI Products with Datasets

Products don’t naturally have “datasets”, but Kineki helps you create one.

Every time you use Kineki, we capture the inputs, outputs, human ratings, feedback, and repairs needed to build high quality models for use in your product. The more you use it, the more data you have.

Your model quality improves automatically as the dataset grows, by giving the models more examples of quality content (and mistakes).

If your product goals shift or new bugs are found (as is almost always the case), you can easily iterate the dataset to address issues.

### Collaborate Across Technical and Non-Technical Teams

When building AI products, there’s usually a subject matter expert who knows the problem you are trying to solve, and a different technical team assigned to build the model. Kineki bridges that gap as a collaboration tool.

Subject matter experts can use our easy to use desktop apps to generate structured datasets and ratings, without coding or using technical tools. No command line or GPU required.

Data-scientists can consume the dataset created by subject matter experts, using the UI, or dive deep with our python library.

QA and PM can easily identify issues sooner and help generate the dataset content needed to fix the issue at the model layer.

The dataset file format is designed to be be used with Git for powerful collaboration and attribution. Many people can contribute in parallel; collisions are avoided using UUIDs, and attribution is captured inside the dataset files. You can even share a dataset on a shared drive, letting completely non-technical team members contribute data and evals without knowing Git.

### Compare Models and Techniques Without Code

There are new models and techniques emerging all the time. Kineki makes it easy to try a variety of approaches, and compare them in a few clicks, without writing code. These can result in higher quality, or improved performance (smaller/cheaper/faster models at the same quality).

Our current beta supports:

- Various prompting techniques: basic, few-shot, multi-shot, repair & feedback
- Many models: GPT, Llama, Claude, Gemini, Mistral, Gemma, Phi
- Chain of thought prompting, with optional custom “thinking” instructions

In the future, we plan to add more powerful no-code options like fine tuning, lora, evals, and RAG. For experienced data-scientists, you can create these techniques today using Kineki datasets and our python library.

### Structured Data

We prioritize data correctness, which makes integrating into AI products easier. No data gets into the dataset without first passing validation, which keeps the dataset clean.

Our easy to use schema UI lets you create and use structured schemas, without knowing JSON-schema formatting. For technical users, we support any valid JSON-schema for inputs and outputs.

### Privacy

Your data stays completely private and local to your machine. We never collect or have access to:

- Datasets / Training Data
- API keys
- Model inputs/outputs (runs)

You can run completely locally using Ollama, or bring your own keys for OpenAI, OpenRouter, Groq, AWS, etc.

_Note: We collect anonymous usage metrics via Posthog analytics (never including dataset content or PII). This can be blocked with standard ad-blockers._

## REST API

[![PyPI - Version](https://img.shields.io/pypi/v/kiln-server.svg?logo=pypi&label=PyPI&logoColor=gold)](https://pypi.org/project/kiln-server/) [![Docs](https://img.shields.io/badge/docs-OpenAPI-blue)](https://kiln-ai.github.io/Kiln/kiln_server_openapi_docs/index.html)

We offer a self-hostable REST API for Kineki based on FastAPI. [Read the docs](https://kiln-ai.github.io/Kiln/kiln_server_openapi_docs/index.html).

The REST API supports OpenAPI, so you can generate client libraries for almost [any](https://github.com/swagger-api/swagger-codegen) [language](https://openapi-generator.tech/docs/generators).

```bash
pip install kineki_server
```

## Contributing & Development

See [CONTRIBUTING.md](CONTRIBUTING.md) for information on how to setup a development environment and contribute to Kineki.



