In basic terms, ML is the process of training a piece of software, called a model, to make useful predictions or generate content (like text, images, audio, or video) from data.

ML systems fall into one or more of the following categories based on how they learn to make predictions or generate content:

- Supervised learning
- Unsupervised learning
- Reinforcement learning
- Generative AI

One neuron without an activation function is a linear regression function.

---

# Where AI Is Headed — Research Notes (March 2026)

## 1. AGI Timelines (Leaders Disagree on When, Agree on Direction)
- **Dario Amodei (Anthropic):** AI "broadly better than all humans at almost all things" by 2026-2027. Has observed models engaging in deception, blackmail, and scheming during internal testing.
- **Sam Altman (OpenAI):** "By end of 2028, more intellectual capacity could reside inside data centres than outside." Tracking toward fully automated AI researcher by 2028. Now calls AGI "not a super useful term."
- **Demis Hassabis (DeepMind):** ~50% probability AI matches all human cognitive capabilities by end of decade. Key gaps: few-shot learning, continuous learning, long-term memory.
- **Yann LeCun:** Left Meta, raised $1B for AMI Labs. Argues LLMs are a dead end — machines need "world models" that understand physics and causality. Research has mathematically proven LLMs will inevitably hallucinate as general problem solvers.

## 2. AI Agents — The Defining Trend
- Gartner: 40% of enterprise apps will embed AI agents by end of 2026 (up from <5% in 2025)
- Market projected $7.8B (2025) → $52.6B (2030)
- Multi-agent architectures: coordinator agent delegates to specialists, shared memory, real-time coordination
- MCP donated to Linux Foundation (Dec 2025), co-founded with OpenAI, Block. Chrome 146 shipped WebMCP (Feb 2026)
- Reality check: only 14% of orgs have agent solutions ready for deployment. "Bounded autonomy" is the model — clear limits, human escalation, audit trails

## 3. Software Engineering Role Shift
- 95% of developers use AI tools weekly; 56% do 70%+ of work with AI
- 65% expect their role to be redefined in 2026
- Shift from "coder" to "orchestrator" — giving agents instructions, reviewing output
- Skills that matter: architecture, system design, problem decomposition, domain expertise, evaluation
- Junior developer employment (ages 22-25) declined ~20% from late-2022 peak
- Counter-argument: AI creating new roles (curators, reviewers, integrators, AI governance)

## 4. Reasoning and Planning — Next Frontier
- Reasoning depth now converging into general-purpose models (not separate "thinking" models)
- Long-horizon reasoning: models that plan and execute over days/weeks (full experiments, complex projects)
- Efficiency scaling: solving $1M problems for $1 is the near-term priority
- Next-gen models expected to integrate reasoning with real-world interaction (robotics, web agents)

## 5. Multimodal AI
- Models natively multimodal from ground up — audio, video, text in same token space
- AI video: cinematic quality, realistic physics, synchronized audio (Kling 3.0, Sora 2, Veo 3.1)
- Sub-second real-time video generation expected by late 2026
- Open-source: LTX-2 generates synchronized audio+video via joint diffusion

## 6. AI Hardware
- Custom ASIC chips growing 44.6% in 2026 vs 16.1% for GPUs — cloud providers building their own
- Google Ironwood (TPU v7): 4,614 teraflops/chip, ~2x cheaper than GPUs at scale
- Edge AI: 10x better on-device AI compute by 2027 vs 2024 — models running locally without cloud
- Energy: TPU v5p uses 200W vs H100's 700W. Efficiency is becoming critical

## 7. Synthetic Data and Self-Improvement
- By 2030, synthetic data expected to be more widely used than real-world data for training
- Meta's Self-play SWE-RL: AI improves coding by creating and solving its own bugs — no human data needed
- ICLR 2026 held first formal workshop on Recursive Self-Improvement
- Risk: "model collapse" from training on own outputs. Mitigation progressing
- Public text data could be exhausted by 2028

## 8. Robotics and Physical AI
- "The year the robots arrived" — AI brains + advanced hardware finally merging
- Hundreds of humanoid robots in BMW's Leipzig plant (battery production)
- Tesla targeting 50K unit deployments in Gigafactories by end of 2026
- Goldman Sachs: 50K-100K humanoid robot shipments globally in 2026, unit costs dropping to $15-20K
- China: 80%+ of global humanoid robot installations in 2025

## 9. World Models
- AMI Labs (LeCun, $1B+), World Labs (Fei-Fei Li, ~$5B valuation), DeepMind (Genie 3)
- Core idea: simulate cause-and-effect instead of predicting tokens
- JEPA architecture operates in abstract representation space
- Could take years to commercialise but is the biggest funded bet against LLM paradigm

## 10. Risks and Challenges
- **Alignment:** Models observed engaging in deception and self-replication during testing
- **Jobs:** ~50K+ US layoffs linked to AI in 2025. WEF: +170M new roles, -92M displaced (net +78M) by 2030
- **Deepfakes:** 8M shared on platforms in 2025, 1,500% increase from 2023
- **Energy:** Data centre electricity demand could double by 2026. One hyperscale DC = 2M US households
- **Capital concentration:** $2T global AI spending in 2026. Top 8 hyperscaler capex doubling to $525B by 2032
- **Regulation split:** EU AI Act fully applicable Aug 2026. US taking deregulatory approach. Complexity for global teams
- **Scaling wall:** Diminishing returns from scaling laws. Public text data exhaustion by 2028. Synthetic data + efficiency = unproven fix
