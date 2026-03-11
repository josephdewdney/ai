# Evolution of AI — Full Script

Today I want to talk about the evolution of AI — where it began and how it got to where we are now. I've grouped the key developments into five eras, based on which approach was dominating the field at the time. You'll notice a lot of overlap — sometimes the research came much earlier than when it became the focus.

> **[OPEN: The Beginnings on the timeline]**

## The Beginnings: 1950 to 1974

> **[TIMELINE: Computing Machinery and Intelligence]**

It starts in 1950, when Alan Turing publishes "Computing Machinery and Intelligence." He asks a simple question: can machines think? And he proposes the Turing Test — if a machine can hold a conversation and you can't tell it apart from a human, does it matter whether it's really thinking?

> **[TIMELINE: Dartmouth Workshop]**

Six years later, in 1956, the Dartmouth Workshop happens. This is considered the birth of AI as a field. It was led by John McCarthy, Marvin Minsky, Nathaniel Rochester, and Claude Shannon. Fun fact — Claude from Anthropic is actually named after Claude Shannon.

> **[TIMELINE: The Perceptron]**

Most of the early work was symbolic AI — programming rules and logic by hand. The one exception was the Perceptron, invented by Frank Rosenblatt in 1957, which was an early neural network that could learn simple patterns. But it was very limited.

> **[TIMELINE: ELIZA]**

Then in 1966, Joseph Weizenbaum creates ELIZA, one of the first chatbots. It could simulate a conversation, and people were genuinely fooled by it — even though it was just pattern matching.

> **[TIMELINE: Lighthill Report]**

The problem with all of these early systems was that they had to be manually programmed, and they fell apart the moment you took them outside their narrow domain. Expectations had been set very high, and the results weren't matching up. In 1973, the Lighthill Report in the UK criticised AI research, leading to funding cuts and the start of the first AI winter.

> **[OPEN: Expert Systems on the timeline]**

## Expert Systems: 1980 to 1987

After the winter, AI came back with narrower ambitions. Instead of trying to build general intelligence, researchers focused on rule-based systems for specific domains. These were called expert systems.

> **[TIMELINE: MYCIN Expert System]**

A key inspiration was MYCIN, developed in 1976, which could diagnose blood infections using about 450 if-then rules. It performed as well as human specialists.

> **[TIMELINE: R1: First Commercial Expert System]**

The first big commercial success was R1, also called XCON, deployed by DEC in 1980. It configured VAX computer orders and saved the company an estimated 25 million dollars a year. This proved that AI had real business value, and suddenly companies were paying attention.

> **[TIMELINE: Fifth Generation Computer Project]**

What made this era possible was a combination of things: proven concepts that survived the first winter, and competitive pressure — Japan launched its Fifth Generation Computer Project in 1982, which pushed the US and UK to invest again.

> **[TIMELINE: Symbolics 3600 Launch]**

These systems ran on expensive specialised LISP machines — the Symbolics 3600, for example, cost anywhere from 50 to over 100 thousand dollars. The AI industry was exceeding a billion dollars a year.

But expert systems were brittle. They couldn't handle uncertainty, they couldn't learn, and they were expensive to maintain. When cheaper general-purpose workstations came along and made LISP machines obsolete, the whole market collapsed.

> **[TIMELINE: DARPA Cancels Autonomous Land Vehicle]**

In 1988, DARPA cancelled its flagship Autonomous Land Vehicle project, signalling the collapse of the billion-dollar Strategic Computing Initiative. This marked the start of the second AI winter.

> **[OPEN: Machine Learning on the timeline]**

## Machine Learning: 1986 to 2012

The next shift was fundamental: instead of programming rules by hand, machines started learning from data.

> **[TIMELINE: Learning Representations by Back-Propagating Errors]**

The key theoretical breakthrough was backpropagation. In 1986, Rumelhart, Hinton, and Williams published their landmark paper showing that you could train multi-layer neural networks by propagating errors backward. This technique is still the backbone of all modern deep learning.

What made this era take off practically was a combination of factors: the internet provided vast amounts of training data, compute kept getting cheaper thanks to Moore's Law, and there were important algorithmic advances like support vector machines and ensemble methods.

> **[TIMELINE: Deep Blue Defeats Kasparov]**

One milestone I should mention is Deep Blue beating Garry Kasparov at chess in 1997. It was a huge moment for AI in the public eye, though it was actually rule-based rather than machine learning.

> **[TIMELINE: A Fast Learning Algorithm for Deep Belief Nets]**

In 2006, Geoffrey Hinton published a paper showing that deep neural networks could be efficiently trained layer by layer. After nearly two decades of neglect, this reignited interest in deep learning.

> **[TIMELINE: Netflix Prize]**

The practical results were things we all use — spam filters, recommendation engines like Netflix's, and fraud detection. Netflix actually offered a million-dollar prize for a 10% improvement to their recommendation algorithm, and over 40,000 teams competed. That showed the power of machine learning on real-world data at scale.

> **[TIMELINE: ImageNet]**

And in 2009, Fei-Fei Li launched ImageNet, a huge image database that became essential for training and benchmarking computer vision models.

The limitation of this era was compute. These methods were powerful, but they needed more processing power than was readily available.

> **[OPEN: Deep Learning on the timeline]**

## Deep Learning: 2012 to 2017

Deep learning is essentially neural networks with many layers. What made it work were several technical breakthroughs that came together.

> **[TIMELINE: ReLU Activation Function]**

ReLU — a simple change to how neurons activate — solved the vanishing gradient problem and made training deep networks much faster.

> **[TIMELINE: Dropout Regularisation]**

Dropout gave us a way to prevent overfitting by randomly disabling neurons during training.

> **[TIMELINE: AlexNet Wins ImageNet]**

The moment that made deep learning the focus was 2012, when AlexNet won the ImageNet competition by a huge margin. That made everyone sit up and pay attention.

> **[TIMELINE: Batch Normalisation]**

Batch normalisation stabilised training further. And crucially, GPUs gave us the raw compute power needed.

> **[TIMELINE: AlphaGo Defeats Lee Sedol]**

In 2016, DeepMind's AlphaGo defeated Lee Sedol at Go — a feat that had been thought to be decades away. That was global news.

> **[TIMELINE: Google Neural Machine Translation]**

Deep learning delivered breakthroughs in image recognition, speech recognition, and machine translation. In 2016, Google replaced its entire translation system with a neural network, dramatically improving quality overnight.

> **[OPEN: Foundation Models on the timeline]**

## Foundation Models: 2017 to present

And that brings us to the current era — foundation models. These are AI models that undergo pre-training on a huge amount of data and can then be applied to a wide range of tasks.

> **[TIMELINE: Attention Is All You Need]**

It all starts with a 2017 paper called "Attention Is All You Need," which introduced the Transformer architecture. Fun fact — even the authors didn't foresee the full impact of what they'd created.

> **[TIMELINE: GPT-3]**

In 2020, OpenAI released GPT-3, a model with 175 billion parameters. It showed that scale itself is an ingredient — the more you scale, the more capabilities emerge.

> **[TIMELINE: ChatGPT]**

Then in November 2022, ChatGPT launched, and AI went from a technical topic to a global conversation almost overnight.

These models can generate code, write summaries, translate languages, and much more. But they're not perfect — they hallucinate, they can be confidently wrong, and there are real questions about bias and reliability.

> **[TIMELINE: Model Context Protocol (MCP) Introduced]**

The field is now moving toward agents — AI systems that can take actions, use tools, and work together. The Model Context Protocol, introduced in 2024, is an open standard for how AI agents communicate.

> **[TIMELINE: Agent Skills]**

And just last year, Anthropic introduced Agent Skills for Claude, letting users automate expertise and workflows.

## And what comes next?

We're already seeing AI agents that can browse the web, write and run code, and coordinate with each other. The next step is likely AI that doesn't just respond to prompts but plans, acts, and follows through on complex tasks autonomously.

Beyond that, there's a lot of work on making models smaller and more efficient — running AI locally on your phone or laptop rather than in the cloud. And on the science side, AI is accelerating research in areas like drug discovery and materials science in ways that were simply not possible before.

Whether that leads to something we'd call artificial general intelligence — that's still an open question. But what's clear is that each era built on the last, and whatever comes next will build on what we have now.

I'll leave it there — I'd love to hear what you all think. Thank you.
