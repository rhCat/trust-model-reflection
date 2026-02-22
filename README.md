# Scratch Board — Zero Trust Framework

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

An interactive scratch board documenting 18 principles of trust in AI-assisted software development, the operational framework to address them, architectural analysis, and the industrialization thesis for software engineering.

**[View Live Board →](https://rhcat.github.io/trust-model/)**

## What This Is

This board is the product of adversarial dialogue between a human practitioner and an AI, exploring the fundamental trust infrastructure problems that emerge when AI enters the software development lifecycle. It survived two rounds of rigorous adversarial analysis.

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

Software is entering the industrialization phase that every physical industry went through decades or centuries ago. AI didn't create the trust problem — it created the *scale* that makes the trust problem impossible to ignore. The 18 principles are the same growing pains metallurgy, construction, aerospace, and pharmaceuticals experienced during their industrialization. The solutions — standards, certification, inspection, liability — are known. Software just hasn't built them yet.

The framework proposes: **contracts, not documentation. Enforcement, not review. Provenance, not trust.**

## How to Use

- **Pan**: Click and drag the canvas
- **Zoom**: Mouse wheel / trackpad scroll
- **Navigate**: Click sections in the left sidebar
- **Filter**: Use tag filters or search
- **Connect**: Use the 🔗 Connect mode to draw relationships
- **Add**: Use the ＋ Note mode to add observations

Your additions are saved to your browser's localStorage.

## Files

```
index.html          # Self-contained static page (deploy this)
scratch-board.jsx   # React source component (for development)
LICENSE             # Apache 2.0
README.md           # This file
```

## Hosting

Single `index.html` — no build step, no dependencies, no server.

GitHub Pages: Settings → Pages → Deploy from branch (main).

## Related

- [L++ (Logic Frame)](https://github.com/rhCat/lpp) — The blueprint execution layer

## Meta

This board was co-created by a human and an AI — the exact scenario Principle #15 describes. The reader is already inside the trust problem the framework identifies.

## License

Copyright 2026 rhCat. Licensed under the Apache License, Version 2.0.
