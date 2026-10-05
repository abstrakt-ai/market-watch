# market-watch
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fabstrakt-ai.github.io%2Fmarket-watch%2F&logo=googlechrome&logoColor=white)](https://abstrakt-ai.github.io/market-watch/)
[![pages-build-deployment](https://github.com/abstrakt-ai/market-watch/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/abstrakt-ai/market-watch/actions/workflows/pages/pages-build-deployment)

Daily highlights on technology, business and economics.

**Live site:** https://abstrakt-ai.github.io/market-watch/

## What is Market Watch?

Market Watch is a static web page that presents a daily research brief on what is happening in the world of technology, business and the economy.

- **Stay current.** Keep track of recent events across technology, business and the economy.
- **Spot what's emerging.** Identify and highlight significant emerging events and shifting signals as they develop.
- **Automated daily briefings.** Content is produced by an AI agentic workflow that watches for developments and summarizes them into a daily briefing.

## How it works

The site is plain HTML, CSS and JavaScript with no build step. It reads the latest briefing from [`data/market-watch.json`](data/market-watch.json), which is updated automatically, and is published with GitHub Pages. See [`data/market-watch.sample.json`](data/market-watch.sample.json) for an example of the data shape.

## Disclaimer

Market Watch is provided for informational purposes only. It is not financial, investment or legal advice, and its summaries are generated automatically and may contain errors.
