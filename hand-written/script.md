
# Evolution of AI

## The Beginnings: 1950 - 1974 (~1 min, including intro)

- Alan Turing's paper
- Dartmouth is what made it the focus - Fun fact: Claude from Anthropic is named after Claude Shannon.
- Mostly symbolic AI - Perceptron exception
- Eliza
- The systems had to be programmed and fell apart outside of their narrow domain.
- Start of first AI winter triggered by Lighthill Report (1973) and US/UK funding cuts

## Expert Systems: 1980 – 1987 (~1 min)

- Rule-based systems
- Narrower ambitions, proven concepts from the first AI winter, and competitive pressure from Japan's Fifth Generation Computer Project (1982) made it possible
- MYCIN (1976) diagnosed blood infections using ~450 rules, inspired the boom
- Ran on expensive specialized LISP machines ($50K–$100K+); cheaper general-purpose workstations ended the era by making them obsolete in 1987
- Commercialisation - R1/XCON configured VAX orders for DEC, saving ~$25M/year. Companies realized they could make money from AI.
- Brittle, couldn't handle uncertainty, couldn't learn
- Second AI winter — DARPA cut AI funding, expert systems too expensive to maintain, LISP machine market collapsed

## Machine Learning: 1986 - 2012 (~1 min)

- Learning from data rather than instructions
- Backpropagation (earlier research), the internet provided vast training data, increased compute (Moore's Law), and algorithmic advances (SVMs, ensemble methods) made it possible
- Practical results: spam filters, recommendation engines (Netflix), fraud detection
- Deep Blue beating Kasparov (rule based though)
- Needing more compute

## Deep Learning: 2012 - 2017 (~2 min)

- Neural Networks many layers deep
- Made possible to GPUs, Big Data, ReLU, dropout, batch normalisation, ...
- AlexNet made it the funding focus
- AlphaGo beating Lee Sedol (2016) was global news
- Image recognition, speech recognition, machine translation (Google Neural MT, 2016), games

## Generative AI & Agents: 2017 - present (~4 min)

### Phase 1: Scaling (2017-2023)
- "AI model that undergoes pre-training on a large amount of data to do a range of tasks"
- "Attention is all you need" - Fun fact: even the authors didn't foresee the full impact.
- GPT-3 showed the benefits of scaling — make it bigger, more capabilities emerge
- ChatGPT public focus

### Phase 2: Reasoning (2024)
- Pre-training scaling hits diminishing returns — just making models bigger stops working as well
- Pivot to test-time compute: spend more compute when answering, not just when training
- OpenAI o1 (Sept 2024) — first reasoning model, trained with RL on verifiable rewards (does the code pass? is the maths right?)
- Models learn to "think longer" before answering

### Phase 3: Agents (Dec 2025)
- Models cross a threshold in long-horizon persistence, tool use, and self-recovery (no more going in circles — recognises it's stuck and tries a different approach)
- Opus 4.5, GPT-5.2 Codex, and other frontier models all ship within weeks of each other
- Coding agents go from broken to working — Karpathy: "coding agents basically didn't work before December"
- Each phase found a new axis to scale: first parameters, then inference compute, then task duration and tool use
- MCP, Agent Skills — open standards and tooling for agents

- Code generation, summaries, translation, ...
- Hallucinations, ...

## And what comes next? (~1 min)


For each section:
    - What is it?
    - What made it possible (both theoretically and practically)?
    - What made it the focus (funding and/or publicly)?
    - What could it do?
    - What were the limitations?
