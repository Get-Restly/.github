<p align="center">
  <img width="100" src="/readme-assets/logo.png" alt="restly logo">
</p>

<h1 align="center">
  Restly
</h1>

<h3 align="center">
  Fastest way to generate tutorials from your OpenAPI spec.
</h3>

<h4 align="center">
  <a href="https://getrestly.com/">Website</a> |
  <a href="https://github.com/Get-Restly/restly-frontend">Front-end repo</a> |
  <a href="https://github.com/Get-Restly/restly-backend">Back-end repo</a>
</h4>

https://github.com/Get-Restly/.github/assets/16181836/f3cf8b7e-e3c7-4182-8909-fde2f89fe433

<!-- <img width="100%" src="/readme-assets/preview.png" alt="Cover image"> -->

## What is Restly?

We use GPT-4 to generate a user-friendly tutorial against any OpenAPI spec. For example:

- Use the VoCode API to set up an automated agent that talks like Yoda and makes references from the Star Wars movies
- Use the Weaviate APIs to import a large dataset of Wikipedia articles
- Use the SendGrid APIs to create a marketing and start an email campaign

This is useful for API providers who want to provide a tutorial for their API and bootstrap something quickly, or for developers who want to learn how to use an API.

## Getting Started

The fastest way to get started is to use our hosted version at [getrestly.com](https://getrestly.com/).

## Repository Structure

We've split frontend and backend across two repos:

1. [Frontend Repo](https://github.com/Get-Restly/restly-frontend)
2. [Backend Repo](https://github.com/Get-Restly/restly-backend)

## Roadmap

- [ ] Validate OpenAPI spec
- [ ] Allow multiple API specs in the same time (Pinecone + VoCode)
- [ ] Execute the actual steps in an actual execution environment to know if the steps are correct vs. hallucinated
- [ ] Edit mode vs. generation mode
- [ ] Take an existing tutorial and check if it's valid against a new OpenAPI spec
