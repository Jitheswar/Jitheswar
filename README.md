# Jitheswar

B.Tech CSE at KL University Hyderabad, class of 2028. I work on ML and systems, and I like results that someone else can check. Open to internships and research work.

[Portfolio](https://jitheswar.github.io) · [Email](mailto:jitheswaredu@gmail.com) · [LinkedIn](https://linkedin.com/in/jitheswar) · [LeetCode](https://leetcode.com/u/Jitheswar/)

## Work

| | Project | What it is |
|---|---|---|
| 01 | **[JithuBrowser](https://github.com/Jitheswar/JithuBrowser)** | A privacy-focused browser built on official Chromium. 23 patches; it passes all 35 tests of its privacy suite on Linux, where stock Chrome fails 31. |
| 02 | **[Craftie](https://github.com/Jitheswar/craftie)** | An AI coworker for Minecraft. It joins your world as a second player, takes requests in chat and works out every step itself. |
| 03 | **[NexCC](https://github.com/Jitheswar/nexcc)** | An optimizing compiler for a C subset where every stage is visible, from automata through SSA to RISC-V, with a VM that steps backwards. Built with a teammate. |
| 04 | **[Diabetic retinopathy screening](https://github.com/Jitheswar/sih26038)** | Screening for rural India (SIH 2026) that checks its own explanations against lesion evidence and sends unclear cases to a person. Validation sensitivity 0.982, specificity 0.917. |
| 05 | **[Agent spend policy engine](https://github.com/Jitheswar/agent-spend-policy-engine)** | Decides whether an AI agent may spend money before it pays. Real payments on Algorand testnet, with an audit log anyone can verify. |
| 06 | **[Ayur-Ai](https://github.com/Jitheswar/Ayur-Ai)** | Identifies Ayurvedic leaves from a photo and looks up their uses. Fully offline, no LLM. 98.6% cross-validated accuracy. |

**Also built**

- **[RSNA knee MRI](https://github.com/Jitheswar/RSNA)**: our team's entry for the RSNA 2026 Kaggle competition. 12 findings, 4,407 studies, only 58 reference labels. Public leaderboard AUC 0.958, blended with two credited public pipelines.
- **[onepass-zsc](https://github.com/Jitheswar/onepass-zsc)**: zero-shot text classification that scores every label in one forward pass, with calibrated probabilities. 0.682 mean accuracy on 13 unseen datasets, against 0.660 for the same backbone run once per label. Team project.
- **[AIDevOps](https://github.com/Jitheswar/aidevops)**: ranks vulnerabilities in a live Kubernetes cluster by how exposed each workload really is. Team project.

## Open source

- **Zephyr RTOS**: two merged fixes, in the DNS resolver ([#123434](https://github.com/zephyrproject-rtos/zephyr/pull/123434)) and the CMake stack-protector setup ([#123198](https://github.com/zephyrproject-rtos/zephyr/pull/123198)).
- **Omarchy**: three open PRs: Bend as a development environment ([#19250](https://github.com/omacom/omarchy/pull/19250)), the Dell G15 touchpad binding at boot ([#17323](https://github.com/omacom/omarchy/pull/17323)), and shell tests that ran the installed commands instead of the checkout's ([#17324](https://github.com/omacom/omarchy/pull/17324)).
- **gpu-unlock**: open PR adding the laptop RTX 3050 6GB ([#327](https://github.com/Zagitta/gpu-unlock/pull/327)).

## On my own machine

Two themes I made for Omarchy, the Linux setup I use every day:

- **[Sadie My Love](https://github.com/Jitheswar/sadie-my-love)**: a copper and oxblood palette that follows the wallpaper.
- **[Chrysos Heirs](https://github.com/Jitheswar/chrysos-heirs)**: a Honkai: Star Rail theme with fourteen palettes, one per heir. Change the wallpaper and the terminal, borders, bar and lock screen follow it.

## How I work

I'd rather publish a failed result than a number nobody can reproduce. My projects keep a written record of what was tried and dropped, not just what shipped. [`Ayur-Ai/experiments/journal.md`](https://github.com/Jitheswar/Ayur-Ai/blob/main/experiments/journal.md) logs all 14 iterations, including the 8 it reverted or rejected, and [`sih26038`](https://github.com/Jitheswar/sih26038#where-it-stands) explains why it turned down a setting that handled more cases on its own: it sent two referable patients home.
