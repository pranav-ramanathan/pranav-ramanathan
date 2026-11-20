# Pranav Ramanathan

MSc Machine Learning at UCL · previously ML SDE Intern at Amazon · Co-founder of Humanaize

MSc Machine Learning student at UCL. I build LLM agents that hold up in production, and I study where learning methods beat classical search and where they do not.

Open to summer 2027 ML research and engineering internships.

## Highlights

- **72% of 212** high-severity incidents where my On Call Copilot at Amazon matched the ground-truth root cause and fix.
- **Frontiers in AI** first-author paper comparing ILP, PatternBoost and PPO on the no-three-in-line problem, plus a poster at the ICML 2026 AI4Math Workshop.
- **50 → 2** open security risks in two weeks, using a remediation agent I built at Amazon that is now used by two other teams.

## Publications

- **Three methods, one problem: classical and AI approaches to no-three-in-line.** Frontiers in Artificial Intelligence, 9:1799444 (2026). [Paper](https://doi.org/10.3389/frai.2026.1799444) · [arXiv](https://arxiv.org/abs/2512.11469) · Code: [ILP](https://github.com/pranav-ramanathan/N3L_gurobi), [PatternBoost](https://github.com/pranav-ramanathan/N3L_PatternBoost), [PPO](https://github.com/pranav-ramanathan/N3L_RL)
- **Four Methods, One Problem: The No-Three-in-Line Problem.** Poster, ICML 2026 AI4Math Workshop (peer-reviewed, non-archival; selected from 346 submissions). [OpenReview](https://openreview.net/forum?id=svadBHt6YN) · Code: [Gradient flow](https://github.com/pranav-ramanathan/N3L_SciML)

In progress:

- **VoicePilot: Pareto Optimization for Low-Latency Streaming Voice Agents.** Research project, UCL with Vizuara. Formalising voice-pipeline control as constrained multi-objective optimisation.
- **HP Protein Folding: Constraint Programming vs Reinforcement Learning.** Manuscript. CP-SAT reached energy −56 on benchmark 3d9; the best previously reported value is −55. [Code](https://github.com/pranav-ramanathan/HP-CSP)

## Experience

**ML SDE Intern, Amazon** (RBKS AI Innovation Lab, Ring) · Jun 2026 to Sep 2026
- Built an On Call Copilot that identified root causes and recommended fixes matching ground truth for 72% of 212 high-severity incidents.
- Cut my team's open security risks from 50 to 2 in two weeks with an event-triggered remediation agent that submits fixes for human approval; now used by two other teams.

**Co-Founder, [Humanaize](https://humanaizelabs.com)** · Aug 2025 to present
- Built an end-to-end voice platform combining Whisper transcription, Cartesia speech synthesis and RAG-based retrieval on AWS with CI/CD.
- Deployed multilingual voice agents across multiple e-commerce sites using Docker and self-hosted LiveKit for concurrent, real-time sessions.

**STRIDE Research Intern, Queen Mary University of London** · Jun 2025 to Aug 2025
- Benchmarked integer programming, transformer and reinforcement-learning approaches to no-three-in-line, reaching optimal solutions up to 19×19 with ILP, 14×14 with PatternBoost and 10×10 with PPO.
- Built a gradient-flow solver in MLX that reaches optimal 2n configurations at n = 18 by recasting the problem as continuous energy minimisation.

**AI Engineer Intern (part-time), TinyMagiq** · Jun 2024 to Apr 2025
- Cut response latency from 30 seconds to 0.5 seconds by optimising the query pipeline and adding real-time streaming.
- Cut inference costs by over 95% by migrating from GPT-4o to Llama 3.3 70B on Groq.

**Software Engineer Intern, Deep Data Mart** · May 2024 to Sep 2024: migrated legacy IBM mainframe data to Google Cloud, halving transfer times with parallel processing.

**Software Engineer Intern, iamneo** · Jul 2023 to Aug 2023: built a GPT-3 HR chatbot for Microsoft Teams and SharePoint, cutting response times by 75% and direct HR requests by 30%.

## Pinned research code

| Repo | What it is |
| --- | --- |
| [N3L_gurobi](https://github.com/pranav-ramanathan/N3L_gurobi) | Integer linear programming (Gurobi) for no-three-in-line; optimal up to 19×19 |
| [N3L_PatternBoost](https://github.com/pranav-ramanathan/N3L_PatternBoost) | PatternBoost transformer for no-three-in-line; optimal up to 14×14 |
| [N3L_RL](https://github.com/pranav-ramanathan/N3L_RL) | PPO agent for no-three-in-line; optimal up to 10×10 |
| [N3L_SciML](https://github.com/pranav-ramanathan/N3L_SciML) | Gradient flow in MLX for no-three-in-line; optimal 2n up to n = 18 |
| [HP-CSP](https://github.com/pranav-ramanathan/HP-CSP) | CP-SAT model of 3D HP protein folding, compared with a deep RL baseline |

## Education

- **MSc Machine Learning**, University College London, 2026 to 2027
- **BSc Mathematics, First Class**, Queen Mary University of London, 2023 to 2026

## Contact

[Website](https://pranavramanathan.me) · [Email](mailto:pranav.ramanathan@gmail.com) · [LinkedIn](https://www.linkedin.com/in/pranav-ramanathan/)
