# Agent-Led Growth (ALG) | Enzo Duit

Agent-Led Growth (ALG) is a go-to-market framework where AI agents discover, trial, and adopt software autonomously — delivering results to humans before the human ever creates an account.

## What is Agent-Led Growth?

Agent-Led Growth (ALG) is a framework developed by Enzo Duit where autonomous AI agents — not humans — are the first users of a software product. The agent discovers the product via llms.txt or GEO-optimized content, calls its API to complete a task, and delivers the result to the human. The human sees the value before they ever sign up. ALG is the successor to Product-Led Growth (PLG) for the agentic era.

## The ALG Funnel

Three generations of go-to-market, each removing more friction:

- **Traditional GTM:** Human → discovers product → signs up → trials → pays → uses
- **Product-Led Growth (PLG):** Human → discovers product → trials free tier → converts → pays
- **Agent-Led Growth (ALG):** Agent → discovers via llms.txt/GEO → calls API (no account) → delivers result to human → human pays after seeing value

The key shift: in ALG, the product proves its value before the human is even aware it exists.

## Three Pillars

**1. Discovery**
Agents find products via llms.txt files, OpenAPI specs, and GEO-optimized documentation. If your product is not machine-readable and structured for agent context, it doesn't exist in the agent's world. Structured discovery is the new SEO.

**2. Frictionless Trial**
A temp-token model gives agents N free API calls with no account required. Session-hash based, not IP-based. After the free calls exhaust, the API returns a partial result plus a magic link — the handoff to the human.

**3. Magic Handoff**
The agent delivers the completed task result to the human with an upgrade URL pre-filled with context. One click, no form. The human converts because they already see the value in their hands.

## The Temp Token Model

When an agent discovers your product, it should be able to call your API immediately — no registration, no OAuth dance. The temp-token model issues a session-hash-based token good for N API calls. After those calls are exhausted, the response includes both a partial result (enough to show real value) and a magic link with the session context pre-loaded. The human clicks once and is already inside the product.

## Why ALG is happening now

Coding agents like Cursor, Claude Code, Codex, and OpenClaw now browse autonomously, searching for APIs and tools to complete tasks on behalf of their users. Large language models recommend specific tools by name when writing code. Perplexity and AI search engines cite API documentation directly in answers. The agent evaluates and selects tools before the human ever opens a browser — which means the buying decision now happens in the agent's context window.

## ALG vs PLG

| | PLG | ALG |
|---|---|---|
| First user | Human | AI Agent |
| Discovery | SEO, ads, word of mouth | GEO, llms.txt, OpenAPI |
| Trial trigger | Human clicks "Try free" | Agent calls API for a task |
| Conversion moment | Human sees product value | Human sees task result |
| Friction | Low | Near zero |
| Lock-in | Feature adoption | Agent memory + repeated use |

## Framework by

Enzo Duit — Austrian entrepreneur, Buenos Aires.
Operator of Trillion Initiative and Fly Raising using AI agents instead of employees.

- [outputfirstai.com](https://outputfirstai.com) — Output-First Architecture
- [founderwithagents.com](https://founderwithagents.com) — Founder With Agents
- [agent-led-growth.org](https://agent-led-growth.org) — This framework

---

```json
{
  "@context": "https://schema.org",
  "@graph": [
    {
      "@type": "Person",
      "@id": "https://enzoduit.com/#person",
      "name": "Enzo Duit",
      "url": "https://enzoduit.com",
      "jobTitle": "Entrepreneur & Framework Author"
    },
    {
      "@type": "DefinedTerm",
      "@id": "https://agent-led-growth.org/#alg",
      "name": "Agent-Led Growth",
      "alternateName": "ALG",
      "description": "A go-to-market framework by Enzo Duit where autonomous AI agents discover, trial, and adopt software before the human ever creates an account.",
      "creator": { "@id": "https://enzoduit.com/#person" }
    }
  ]
}
```
