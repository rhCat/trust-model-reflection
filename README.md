# Scratch Board — Zero Trust Framework

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

An interactive scratch board documenting 18 principles of trust in AI-assisted software development, the operational framework to address them, architectural analysis, and the industrialization thesis for software engineering.

**[View Live →](https://rhcat.github.io/trust-model/)**

## What This Is

This framework is the product of adversarial dialogue between a human practitioner and an AI, exploring the fundamental trust infrastructure problems that emerge when AI enters the software development lifecycle. It survived two rounds of rigorous adversarial analysis.

**115 notes across 10 sections:**

| Section | Notes | Purpose |
|---------|-------|---------|
| Principles | 19 | The 18 core problems + context |
| Operational Framework | 15 | Six pillars, contract mechanisms, economic layer |
| Architecture | 8 | The raft, the ocean, the waterline |
| Industrialization | 12 | Historical pattern, bridge economics, the old gods |
| Adversary Analysis R1 | 16 | First round of structural attacks |
| Rebuttals R1 | 14 | First round defense |
| Adversary Analysis R2 | 13 | Second round attacks |
| Rebuttals R2 | 13 | Second round defense |
| Meta | 5 | Self-referential observations |

## The Core Thesis

Software is entering the industrialization phase that every physical industry went through decades or centuries ago. AI didn't create the trust problem — it created the *scale* that makes the trust problem impossible to ignore.

The framework proposes: **contracts, not documentation. Enforcement, not review. Provenance, not trust.**

## Files

```
index.html          # Cover page — narrative guide with deep links to every note
board.html          # Interactive scratch board (pan, zoom, connect, add)
scratch-board.jsx   # React source component (for development / Claude artifact)
LICENSE             # Apache 2.0
README.md           # This file
```

## Deep Linking

The board supports URL-based navigation to individual notes:

```
board.html?note=principle001    → pans to Principle #1
board.html?note=arch003         → pans to The Waterline
board.html?section=Meta         → opens the Meta section
```

The cover page (`index.html`) uses these deep links for every note.

## Hosting

No build step. No dependencies. No server.

GitHub Pages: Settings → Pages → Deploy from branch (main). The `index.html` cover page is the entry point, linking into `board.html` for the interactive board.

## Related

- [L++ (Logic Frame)](https://github.com/rhCat/lpp) — The blueprint execution layer

## License

Copyright 2026 rhCat. Licensed under the Apache License, Version 2.0.
