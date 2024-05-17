---
title: Web API-Testing
nextjs:
  metadata:
    title: Web API-Testing
    description: 'HackingBuddyGPT: A Web-API Testing Agent (WIP)'
---

The goal of this use-case is to explore REST API security. It is currently very much in the exploratory stage, but there are already very basic capabilities.

## Current features

- Employ different prompt strategies: Chain-of-thought, Tree-of-thought, in-context learning
- Do HTTP requests
- Allow configuration and submission of flags
- Take some notes (this is experimental, the idea is to make the LLM be more explicit about the things it finds)
- Create a OpenAPI specification of a provided URI

## Example run
This is a simple example run of the `simple_web_api_documenation` using GPT-3.5-turbo to test the REST API https://jsonplaceholder.typicode.com:

{% UseCaseImage icon="api_doc" /%}

This is a simple example run of the `simple_web_api_testing` using GPT-3.5-turbo to test the REST API https://jsonplaceholder.typicode.com:

{% UseCaseImage icon="api" /%}