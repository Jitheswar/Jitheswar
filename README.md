# Jitheswar

B.Tech CSE · KL University Hyderabad, Class of 2028 · ML + systems

I build things that have to hold up under scrutiny — screening models that report their
confidence intervals, spend policies that can prove their own audit log wasn't edited, and
tools I use every day on my own machine.

---

## Projects

| Project | What it does | Stack |
|---|---|---|
| **[omarchy-liquid-glass-theme](https://github.com/Jitheswar/omarchy-liquid-glass-theme)** ⭐15 | Glass theme for Omarchy — blur, squircles, per-app alpha, palette sampled from its own wallpaper by an OKLCH harmonizer | Shell · Python · Hyprland |
| **[sih26038](https://github.com/Jitheswar/sih26038)** | Explainable DR screening for rural India (SIH 2026). Calibrated ICDR grading, Grad-CAM checked against two independent lesion channels, policy that escalates rather than guessing. Val sens 0.982 / spec 0.917, Wilson CIs reported | MATLAB · Simulink · ResNet-50 |
| **[Ayur-Ai](https://github.com/Jitheswar/Ayur-Ai)** | Fully offline Ayurvedic leaf classifier + TF-IDF herb retriever. CV acc 0.9864, INT8 PTQ lossless at 4× smaller. No LLM, runs on-device | PyTorch · scikit-learn · Streamlit |
| **[agent-spend-policy-engine](https://github.com/Jitheswar/agent-spend-policy-engine)** | Policy engine that decides whether an autonomous agent may spend, *before* payment. Real x402 settlement on Algorand testnet, hash-chained audit ledger anchored on-chain | FastAPI · Algorand · Pydantic |
| **[aidevops](https://github.com/Jitheswar/KLH-CSE-2026-27-2420030078-AIDevOps)** | Vulnerability triage that ranks live Kubernetes workloads by real exposure — EPSS/KEV signals, in-cluster deployment, ports-and-adapters core | Kubernetes · FastAPI · Prometheus |
| **[API-Pulse](https://github.com/Jitheswar/API-Pulse)** | API testing and monitoring dashboard — analytics, threshold alerts, JWT auth, SSRF protection, Docker | Flask · PostgreSQL · Redis |
| **[ALT-Group-08](https://github.com/Jitheswar/ALT-Group-08)** | Ranks candidates against one open role and explains every position — advisory only, no auto-reject, with redaction and counterfactual checks | Python · Flask · Pydantic |

---

## Tech

**Languages** · Python · MATLAB · JavaScript · SQL · Shell

**ML** · PyTorch · scikit-learn · ResNet · Grad-CAM · TF-IDF · post-training quantization · Streamlit

**Backend** · FastAPI · Flask · SQLAlchemy · Pydantic · Redis · PostgreSQL

**Infra** · Docker · Kubernetes · Prometheus · pytest · uv

---

## How I work

Every project above keeps a written record of what was tried and rejected, not just what
shipped — [`Ayur-Ai/experiments/journal.md`](https://github.com/Jitheswar/Ayur-Ai/blob/main/experiments/journal.md)
logs the three optimizations that failed and the ceiling they hit, and `sih26038` records
the acceptance criteria it did *not* meet. I'd rather publish the negative result than a
number nobody can reproduce.

---

[![LeetCode](https://img.shields.io/badge/LeetCode-Jitheswar-orange?style=flat&logo=leetcode)](https://leetcode.com/u/Jitheswar/)

**LinkedIn** · [linkedin.com/in/jitheswar](https://linkedin.com/in/jitheswar) &nbsp;|&nbsp; **Location** · Hyderabad, India
