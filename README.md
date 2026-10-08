# market-watch
[![Website](https://img.shields.io/website?url=https%3A%2F%2Fabstrakt-ai.github.io%2Fmarket-watch%2F&logo=googlechrome&logoColor=white)](https://abstrakt-ai.github.io/market-watch/)
[![RSS](https://img.shields.io/badge/rss-subscribe-ff9900?logo=rss&logoColor=white)](https://abstrakt-ai.github.io/market-watch/feed.xml)
[![pages-build-deployment](https://github.com/abstrakt-ai/market-watch/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/abstrakt-ai/market-watch/actions/workflows/pages/pages-build-deployment)

Daily highlights on technology, business and economics.

**Live site:** https://abstrakt-ai.github.io/market-watch/

**RSS:** https://abstrakt-ai.github.io/market-watch/feed.xml

## What is Market Watch?

Market Watch is a static web page that presents a daily research brief on what is happening in the world of technology, business and the economy.

- **Stay current.** Keep track of recent events across technology, business and the economy.
- **Spot what's emerging.** Identify and highlight significant emerging events and shifting signals as they develop.
- **Automated daily briefings.** Content is produced by an AI agentic workflow that watches for developments and summarizes them into a daily briefing.

## Subscribe and machine-readable feeds
The HTML page loads JSON in the browser. For readers and agents, prefer these files (no JavaScript):
| Format | URL |
| --- | --- |
| RSS | https://abstrakt-ai.github.io/market-watch/feed.xml |
| Markdown (today) | https://abstrakt-ai.github.io/market-watch/today.md |
| JSON (today) | https://abstrakt-ai.github.io/market-watch/data/market-watch.json |
| Agent index | https://abstrakt-ai.github.io/market-watch/llms.txt |

Add the live site URL or `feed.xml` to a feed reader to subscribe. Each RSS item is one daily highlight.

Agents: start at [`llms.txt`](https://abstrakt-ai.github.io/market-watch/llms.txt), then fetch markdown or RSS, not the HTML.


## Disclaimer

Market Watch is provided for informational purposes only. It is not financial, investment or legal advice, and its summaries are generated automatically and may contain errors.
