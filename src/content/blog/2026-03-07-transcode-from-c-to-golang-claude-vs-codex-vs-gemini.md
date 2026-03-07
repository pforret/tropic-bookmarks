---
title: "Transcode from C to Golang: Claude vs Codex vs Gemini"
description: "Compared Claude Code, Codex CLI & Gemini CLI for transcoding a 5000-line C audio tool to Go. Codex won clearly."
pubDate: "2026-03-07T22:59:00.498Z"
url: "https://blog.forret.com/2025/2025-09-20/transcode-c-to-golang/"
heroImage: "/bookmarks/1772924331832.jpg"
---

A developer working in digital cinema needed a CLI tool to measure LEQ(m) loudness — an ISO standard for cinema audio. The only open-source option was a 5000-line C file, last touched in 2020, and the author hadn't written C in 30+ years.

Rather than learn C again, they asked three AI coding agents — Claude Code, OpenAI Codex CLI, and Gemini CLI — to transcode the program to Go. This became a real-world benchmark: same task, same source code, three AI tools.

The winner was OpenAI's Codex CLI, which produced the most complete and functional Go port. Claude Code and Gemini CLI both struggled with various aspects of the conversion. The results and the generated Go code are published on GitHub at github.com/pforret/leqm-nrt.

[Read more](https://blog.forret.com/2025/2025-09-20/transcode-c-to-golang/)
