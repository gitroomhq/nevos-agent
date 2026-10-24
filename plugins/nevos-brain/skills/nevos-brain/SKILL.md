---
name: nevos-brain
description: Answer marketing, distribution and growth questions from Nevo David's playbooks through the Nevo's Brain MCP server. Use when the user asks how to get users or customers, find a niche, ride a trend, pick a channel, launch, price, or grow a product.
---

# Nevo's Brain

Nevo's Brain is a searchable library of Nevo David's playbooks: how he grew Postiz, a bootstrapped SaaS, to millions in ARR. It comes from his X articles, talks and podcast interviews.

## When to use

- The user asks how to get users, customers, signups or traffic
- Finding a niche or an idea people already pay for
- Catching a hype or trend early
- Picking a channel: open source, directories, Product Hunt, X, LinkedIn, Reddit, SEO, partnerships
- Launches, pricing, or growing MRR

## Instructions

1. Call `search_brain` with one topic in plain words, for example "launching on Product Hunt" or "getting the first 100 users".
2. If the passages don't answer the question, search again with different words or a narrower topic. Two or three searches are normal for a broad question.
3. Call `list_sources` when the user asks what the brain covers.
4. Answer from what the passages say. Keep their numbers and examples, and name the source of each tactic.
5. Apply the tactics to the user's product. If the brain has nothing on a point, say so instead of filling the gap.

The server signs you in once with your email (OAuth). It is free.
