# Christophe VG's Agentic Marketplace

[![Platform](https://img.shields.io/badge/platform-mac%20%7C%20linux-lightgrey.svg)][platform]
[![License](https://img.shields.io/github/license/christophevg/marketplace.svg)][license]
[![Agentic](https://img.shields.io/badge/workflow-agentic-blueviolet?style=flat-square)](https://christophe.vg/about/Agentic-Workflow)

The repository contains my very own Agentic Marketplace, offering access to plugin distributions of skills, agents and MCP servers I like to share.

## Minimal Survival Instructions

1. In your runtime environment, ensure `fastmcp` is installed:

```console
pip install fastmcp
```

2. Inside Claude

```
/plugin marketplace add christophevg/marketplace
/plugin install demo-plugin@christophe.vg
```

> For now there is just a `demo-plugin`. But no worries, there is more to come 😇

3. Using the demo plugin

```console
 ▐▛███▜▌   Claude Code v2.1.114
▝▜█████▛▘  glm-5:cloud · API Usage Billing
 ▘▘ ▝▝    ~/Workspace/agentic

❯ /demo-plugin:hello Christophe

⏺ Hello Christophe! 👋

 It's great to connect with you again. I'm Eira, ready to be your calm and 
 capable companion as we work together.

 What would you like to focus on today? Whether it's continuing work on c3, the
 incubator, your website, or exploring something new — I'm here to help you make
 progress.

❯ Roll a dice!

⏺ 🎲 You rolled a 4!

 Want to roll again?

────────────────────────────────────────────────────────────────────────────────
❯ 
────────────────────────────────────────────────────────────────────────────────
 glm-5:cloud: █░░░░░░░░░ 15% | ⏱️  1m 32s
 📁 c3 | 🌿 master
```

[platform]: #
[license]: LICENSE
