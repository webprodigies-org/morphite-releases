---
id: cheaper-parallel-workers-0-6-6
title: "Parallel workers are much cheaper"
date: 2026-10-15
version: 0.6.6
tags: [improved, fixed]
summary: "A room's first messages use about half the tokens, and project icons keep their full colour."
---

## Improved

- **Parallel workers are much cheaper.** A room's first messages use about half the tokens, because workers share one cached start and load only what they need.

## Fixed

- **Project icons keep their full colour.**
