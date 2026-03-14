# Ghost Repurpose

**One newsletter. Five formats.**

Paste your Ghost newsletter post and get AI-generated content for every channel — Twitter/X thread, LinkedIn post, podcast show notes, re-engagement email, and a key takeaway summary — all in your voice.

Built by [Roman Martins](https://romanmartins.com) using the Claude API.

## What it does

Ghost creators spend hours manually rewriting each newsletter issue for different platforms. Ghost Repurpose eliminates that. One paste, five formats, all voice-matched to your publication.

**Formats generated:**
- **Twitter/X Thread** — hook tweet + numbered thread, max 8 tweets, each under 280 chars
- **LinkedIn Post** — strong first line, short paragraphs, no hashtags, algorithm-friendly
- **Podcast Show Notes** — spoken-word format with talking points a host can riff off
- **Re-engagement Email** — for subscribers who didn't open, with subject line included
- **Key Takeaway Summary** — under 100 words, usable as a Ghost post header or preview

## Why voice matters

The "describe your voice" field is the most important input. It's what makes the output sound like *you* instead of generic AI content. Be specific: "Direct and data-driven. I never use marketing speak. My readers are senior operators."

## Stack

- Vanilla HTML/CSS/JS (single file, no build step)
- Vercel serverless function (Node.js)
- Anthropic Claude API (`claude-sonnet-4-6`)

## Deploy

1. Fork or clone this repo
2. Deploy to Vercel
3. Add `ANTHROPIC_API_KEY` as an environment variable in Vercel dashboard
4. Done

## Part of Roman's Lab

This tool is part of [Roman's Lab](https://sinkrest.github.io/romans-lab) — a collection of AI-powered PM tools built by Roman Martins.

[romanmartins.com](https://romanmartins.com) · [GitHub](https://github.com/sinkrest)
