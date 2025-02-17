![Axflow banner](./assets/banner.jpg)

# The TypeScript framework for AI development

![Github CI](https://github.com/axflow/axflow/workflows/Github%20CI/badge.svg) [![Slack](https://img.shields.io/badge/Join%20Our%20Community-Slack-blue)](https://join.slack.com/t/axilladevelopers/shared_invite/zt-212wj3ek0-NHzIFtVg1lxL1t0ViPbysA)
<a href="https://app.greptile.com/repo/axflow"><img src="https://img.shields.io/badge/learn_with-greptile-%091B12?color=%091B12" alt="Learn this repo using Greptile"></a>

Axflow is a collection of modules for building robust natural language powered applications. These modules can be adopted incrementally, thus providing a modular and scalable solution.
Used together, they form an end-to-end framework for developing AI applications.

# Modules

- [**@axflow/models**](./packages/models/) &mdash; A zero-dependency, modular SDK for building robust natural language applications. Includes React hooks and streaming utilities that make building AI applications a breeze.
- [**axgen**](./packages/axgen/) &mdash; A framework for connecting your data to large language models
- [**axeval**](./packages/axeval/) &mdash; A framework for evaluating LLM output quality

In addition to the above modules, we're working on the following modules:

- **extract**: A library for efficient data processing, particularly loading, transforming, and chunking documents from arbitrary sources. Most useful for applications that need to load and preprocess data for vector search.
- **serve**: A serving framework to run any LLM model (OSS or otherwise). It will also provide middleware options for user throttling, analytics, and logging
- **finetune**: A library focused on fine-tuning models

## [Documentation](https://docs.axflow.dev)

# Goals

Axflow aspires to deconstruct the complex paradigms of working with LLMs into manageable and intuitive components.
Our library takes a code-first approach, emphasizing the importance of flexibility and control for developers.
As a foundational framework, Axflow empowers developers to build higher-level TypeScript AI features and products seamlessly.

## Examples

Here is an example [open source UI](https://github.com/axflow/original-demo-ui) showcasing what our first module, axgen, can do, with a [short video](https://www.loom.com/share/458f9b6679b740f0a5c78a33fffee3dc) walkthrough.

## License

[MIT](LICENSE.md)
