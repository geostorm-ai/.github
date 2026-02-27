<div align="center">

[![GeoStorm](https://img.shields.io/badge/geostorm--ai%2Fgeostorm-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/geostorm-ai/geostorm)

# GeoStorm

### AI Perception Monitoring for Software

**Monitor how AI systems perceive and recommend your software across GPT, Claude, Gemini, and more.**

<p align="center">
  <a href="https://github.com/geostorm-ai/geostorm">
    <img src="https://img.shields.io/badge/python-3.11+-blue?style=flat&logo=python&logoColor=white" />
  </a>
  <a href="https://github.com/geostorm-ai/geostorm/pkgs/container/geostorm">
    <img src="https://img.shields.io/badge/docker-ghcr.io-2496ED?style=flat&logo=docker&logoColor=white" />
  </a>
  <a href="https://github.com/geostorm-ai/geostorm?tab=contributing-ov-file">
    <img src="https://img.shields.io/badge/PRs-welcome-brightgreen?style=flat" />
  </a>
  <a href="https://github.com/geostorm-ai/geostorm?tab=MIT-1-ov-file">
    <img src="https://img.shields.io/badge/license-MIT-blue?style=flat" />
  </a>
</p>

### Star us on GitHub

<a href="https://github.com/geostorm-ai/geostorm">
  <img src="https://img.shields.io/badge/Star%20on%20GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="Star GeoStorm" />
</a>

</div>

---

## What GeoStorm Does

Developers increasingly discover software through AI — "what's the best library for X?" shapes adoption. But you have no idea what these models are saying about your project.

GeoStorm monitors multiple AI models on a schedule, tracks how they perceive and recommend your software, and alerts you when things change — a new competitor appears, your ranking drops, or a model stops mentioning you.

One container, one command:

```bash
docker run -d -p 8080:8080 -v geostorm-data:/app/data --name geostorm ghcr.io/geostorm-ai/geostorm
```

---

## What We Monitor

| Signal | What It Means |
|--------|---------------|
| **Competitor Emergence** | A new competitor appeared in AI recommendations |
| **Disappearance** | Your software stopped being mentioned by a model |
| **Recommendation Share Drop** | Your share of AI recommendations declined |
| **Position Degradation** | You're being listed lower in rankings |
| **Model Divergence** | Different AI models are giving different answers about you |

---

## Get Involved

**Main repo:** [geostorm-ai/geostorm](https://github.com/geostorm-ai/geostorm)

- **Found a bug?** [Create an issue](https://github.com/geostorm-ai/geostorm/issues/new?template=bug_report.md)
- **Feature idea?** [Submit a request](https://github.com/geostorm-ai/geostorm/issues/new?template=feature_request.md)
- **Want to contribute?** [Read the contributing guide](https://github.com/geostorm-ai/geostorm/blob/main/CONTRIBUTING.md)

---

<div align="center">

**License:** MIT | **Built with:** [Shotgun](https://shotgun.sh/)

</div>
