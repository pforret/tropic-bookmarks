---
title: "Idea: A spectrogram for videos"
description: "Built a video 'spectrogram' tool in Go with AI help: X=time, Y=dominant colors per frame. 5-10x speedup via multithreading. #colorduce"
pubDate: "2026-03-07T22:54:30.983Z"
url: "https://blog.forret.com/2025/2025-09-27/a-spectrogram-for-videos/"
heroImage: "/bookmarks/1772924060477.jpg"
---

What if you could represent an entire video as a single image, with time on the X-axis and dominant colors on the Y-axis — like a spectrogram, but for visuals? That was the vague idea that turned into colorduce, a working Go tool built in about three hours with AI assistance.

The approach converts frame pixels from RGB to HSL, divides the color space into buckets across hue/saturation/luminance axes, builds a histogram per frame, and renders the most-populated color buckets as vertical pixel columns. The result is a compact visual fingerprint of a video's color palette over time.

Development started as a voice conversation with Google Gemini during the commute home. Gemini helped refine the concept, generated the initial Go code, and fixed early errors. A later prompt — essentially 'make it faster' — introduced goroutine-based parallel processing, achieving a 5-10x speedup. The author, not proficient in Go, had a working multithreaded program by end of evening.

Source code: github.c

[Read more](https://blog.forret.com/2025/2025-09-27/a-spectrogram-for-videos/)
