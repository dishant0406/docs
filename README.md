# WhyOps Docs

This repository contains the Mintlify documentation for WhyOps.

WhyOps is deployed in production and provides AI agent observability and automated evaluations.

## Development

Install Mintlify CLI:

```bash
npm i -g mintlify
```

Run the docs locally from the folder with `mint.json`:

```bash
mintlify dev
```

## Structure

- `/getting-started`: Intro and quickstart guides.
- `/core-concepts`: Deep dives into traces, threads, invisible signatures, and evaluations.
- `/architecture`: Technical architecture of the proxy, analyse, auth, and frontend services.
- `/integrations`: Drop-in guides for OpenAI and Anthropic.
