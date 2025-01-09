# Welcome Prime Engine 1.0.0 Open Beta Release!
### Improved AI Engine speed
### Improved AI models structure
### Refractored old LLM models
### Improved AI agents
### Major and minor bug fixes.

# Prime Engine - Solana AI Agents Creating Framework

Prime is a powerful, modular, and highly extensible framework designed for developers building applications that require a seamless blend of performance, flexibility, and scalability. With Prime, you can harness the power of modern tools to craft cutting-edge solutions across industries.

---

## Contract Address and Development Funding
This project is powered by a single, official smart contract address. Please ensure that you interact only with the following address to avoid fraud or misrepresentation:

## Contract Address $PRIME:
`pr1Me7tWgYawfbZMLQDxoL7bD6KhyBYctp72rEengmW`

## DEX: https://dexscreener.com/solana/pr1Me7tWgYawfbZMLQDxoL7bD6KhyBYctp72rEengmW
## WEB: https://primengine.ai/
## X: https://x.com/primengineai
## TG: https://t.me/primengineai

All development and maintenance of this project are funded exclusively through the creator's wallet associated with the token.

## Why PRIME?
- Developer-Centric: Designed with developers in mind, PRIME simplifies complex processes and accelerates development.
- Open-Source: Fully open-source, ensuring transparency and community-driven growth.
- Adaptable: Built to accommodate a wide range of industries and applications, from startups to enterprises.

## Key Features

### 🚀 High Performance
Prime is optimized for speed and efficiency, ensuring your applications run smoothly even under heavy workloads.

### ⚙️ Modularity
With a modular design, Prime allows you to integrate only the components you need, keeping your applications lightweight and focused.

### 📈 Scalability
Whether you're starting small or building enterprise-grade solutions, Prime adapts to your needs, growing with your application.

### 🔒 Security First
Built with security in mind, Prime provides robust tools to safeguard your application and its users.

### 🧩 Extensibility
Easily customize and expand Prime's functionality with plugins, libraries, and APIs tailored to your project's needs.


## Getting Started

First install the package via PyPi.
```bash
pip install prime-agents-py
```
Then define your agent, give it the tools it needs and run it!
```py
from prime import CodeAgent, DuckDuckGoSearchTool, HfApiModel

agent = CodeAgent(tools=[DuckDuckGoSearchTool()], model=HfApiModel())

agent.run("Tell me Solana and Bitcoin price in March 2025")
```


## Contributing
We welcome contributions! If you want to report a bug, suggest a feature, or contribute code, please:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Submit a pull request.

## How strong are open models for agentic workflows?

We've created `CodeAgent` instances with some leading models, and compared them on [this benchmark](https://huggingface.co/datasets/m-ric/agents_medium_benchmark_2) that gathers questions from a few different benchmarks to propose a varied blend of challenges.

## Citing prime

If you use `prime` in your publication, please cite it by using the following BibTeX entry.

```bibtex
@Misc{prime,
  title =        {`prime`: The easiest way to build efficient solana agentic systems.},
  author =       {primengine inc.},
  howpublished = {\url{https://github.com/primengine/prime}},
  year =         {2025}
}
```
