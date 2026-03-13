---
title: "Crawl entire websites with a single API call using Browser Rendering · Changelog"
description: "Cloudflare Browser Rendering adds a /crawl endpoint: submit one URL, get a full site back as HTML, Markdown, or JSON. Now in open beta."
pubDate: "2026-03-13T05:47:32.277Z"
url: "https://developers.cloudflare.com/changelog/post/2026-03-10-br-crawl-endpoint/"
heroImage: "/bookmarks/1773380841408.png"
---

Cloudflare's Browser Rendering API now includes a /crawl endpoint in open beta. Submit a starting URL and it automatically discovers, headless-renders, and returns content from the entire website in your choice of HTML, Markdown, or structured JSON — all in a single API call.

Crawl jobs run asynchronously: you get a job ID on submission and poll for results as pages are processed. The endpoint operates as a signed-agent that respects robots.txt and Cloudflare's AI Crawl Control by default, keeping crawlers compliant with site owner guidance.

Primary use cases are training datasets, RAG pipelines, and content monitoring. It's a notable addition for developers building AI applications who need clean, structured web content without standing up their own crawler infrastructure.

[Read more](https://developers.cloudflare.com/changelog/post/2026-03-10-br-crawl-endpoint/)
