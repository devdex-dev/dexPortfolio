# dexPortfolio

Source for [by-dex.onrender.com](https://by-dex.onrender.com) — a single-page portfolio site showcasing n8n automation workflows and side-project design work.

## Stack
Single static `index.html` — no build step, no framework. Client-side JS handles the category filter for the project grid.

## Structure
- `index.html` — the entire site (styles, markup, and filter script in one file)

## Content
Project cards summarize automation workflows built in n8n (AI agents, lead qualification, data hygiene, RAG pipelines, backup/monitoring infrastructure) plus a "Side Quests" section for Canva/design work outside the automation stack.

## Deploy
Static hosting on Render, serving `index.html` directly.
