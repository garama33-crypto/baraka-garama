# Telecom Network Intelligence Agent

## Overview

AI-powered Telecom Intelligence Agent built with:

- n8n
- OpenAI GPT-4.1-mini
- Gmail

The agent automatically:

- Searches telecom and networking updates
- Tracks IMS and SIP developments
- Monitors telecom security news
- Summarizes findings
- Sends an email digest

---

## Architecture

```text
Manual Trigger
      ↓
AI Agent
      ↓
OpenAI Chat Model
      ↓
Gmail
