# dev-productivity-engine

> Developer Productivity & Tooling Content Engine — Automated high-quality technical articles, tutorials, and roundups for Dev.to + GitHub Pages with affiliate integration.

## Overview

This project generates and publishes consistent, high-value developer content (tutorials, tool roundups, workflow optimizations, "one-evening builds") to Dev.to and your personal GitHub Pages site. It embeds natural affiliate links and drives traffic to your GitHub Sponsors and other projects.

**Proven model**: Consistent technical content publishing on Dev.to and personal blogs reliably builds audience, affiliate income, and sponsorships for developers.

## Autonomous Flow

Cron job → Local LLM generates/updates Markdown → Publishes to Dev.to API → Commits to GitHub Pages → Optional social amplification.

## Income Streams

- Affiliate links in articles (tools, books, hardware)
- GitHub Sponsors growth from authority
- Long-term: Authority that supports all your other projects

## Quick Start (VS Code / Cursor)

Same as the other repos:
1. Clone + venv + `pip install -r requirements.txt`
2. Set up Ollama (recommended)
3. `cp .env.example .env`
4. `python scripts/generate_and_update.py --dry-run`
5. Set up cron/systemd for regular publishing

## Project Structure

Similar structure to saas-alternatives-directory with content-focused scripts.

## Roadmap

- Core generation & Dev.to auto-posting
- GitHub Pages blog publishing
- Affiliate link management
- Performance tracking of published content

*Scaffolding added by Grok — June 2026. Ready for extension in Cursor.*