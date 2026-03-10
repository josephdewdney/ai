# The Evolution of AI — Info Chunk Script

**Target: ~10 minutes**

---

So, I've been using AI and coding agents more and more recently, as I'm sure a lot of you have been as well, and I became increasingly curious as to how we actually got here. I studied neural networks, biologically inspired optimization algorithms and the like in my mathematics degree, and I've followed the developments closely, but I didn't have the overall picture. So I did some research — with help from Daniel and Timo — and found it quite interesting and actually quite telling. We decided it would be a good topic to kick off a series of AI info chunks. In future sessions we can pick particular topics to go deeper into and perhaps pour some cold water on some of the AI hype, so keep in mind what you'd want to learn more about during this talk.

---

**Early Enthusiasm, Great Expectations**

1950. Alan Turing publishes "Computing Machinery and Intelligence" and asks a simple question: can machines think? He proposes the Turing Test — if a machine can hold a conversation and you can't tell it apart from a human, does it matter whether it's "really" thinking?

That question lit a fire. In 1956, a group of researchers met at Dartmouth College — John McCarthy, Marvin Minsky, Claude Shannon, and others. They coined the term "artificial intelligence" and they were wildly optimistic. They genuinely believed that within a generation, machines would be able to do anything a human mind could do.

---

*(continuing Early Enthusiasm)*

In 1966, a program called ELIZA was created at MIT. It was basically a chatbot — it used pattern matching to simulate a therapist. Some people genuinely believed they were talking to something that understood them. It was the first time software created that illusion of intelligence.

Around the same time, researchers were building symbolic AI — "Good Old-Fashioned AI." Encode human knowledge as rules. If this, then that. Expert systems took this approach and ran with it. For narrow problems, they worked well.

---

**A Dose of Reality**

But these systems were brittle. They couldn't handle ambiguity or learn from new data. Funding dried up. Twice. The first AI winter hit in the mid-1970s. Interest came back in the 80s with expert systems, but when those failed to deliver, a second winter followed in the late 80s and early 90s.

There's a pattern here that repeats throughout AI history: hype, followed by reality, followed by disappointment. Keep that in mind.

---

**Statistical Learning**

What pulled AI out of the cold was a philosophical shift. Instead of telling a computer the rules, you give it data and let it figure out the rules itself. That's machine learning.

The concept of neural networks goes back to the 1940s. In 1957, Frank Rosenblatt built the Perceptron — a simple network that could learn to classify inputs. But it was limited, and interest collapsed after Minsky and Papert proved those limitations in 1969.

The breakthrough came in the 1980s with backpropagation — a method for training multi-layer networks. Suddenly, neural networks could learn complex patterns. But they still needed more data and compute than was available.

Meanwhile, other approaches thrived. Support vector machines, random forests, boosting — these became the workhorses of practical AI through the 90s and 2000s. Spam filters, recommendation engines, fraud detection — that was all machine learning.

---

**The Deep Learning Revolution**

Then, 2012. A neural network called AlexNet won the ImageNet competition by a massive margin. It used convolutional neural networks running on GPUs — techniques that had been around for decades. But now three things had converged: the algorithms, the data thanks to the internet, and the compute thanks to GPUs originally designed for video games.

What followed was an explosion. In 2014, GANs showed AI could generate realistic images. In 2016, AlphaGo beat the world champion at Go — a game so complex that brute-force search was impossible. It had to develop something that looked like intuition.

---

**The Foundation Model Era**

In 2017, Google published "Attention Is All You Need." The transformer architecture fundamentally changed natural language processing. The key insight: instead of processing text sequentially, the model could look at all parts of the input simultaneously and learn which parts are relevant to each other.

This architecture scaled incredibly well. And when you scaled it up, something unexpected happened — the models developed capabilities nobody explicitly programmed. Reasoning. Code generation. Translation. These are what researchers call emergent properties.

GPT-2 in 2019 showed a large language model could generate surprisingly coherent text. GPT-3 in 2020, with 175 billion parameters, showed that scale itself was an ingredient — the more you scaled, the more capabilities emerged. And in late 2022, ChatGPT brought all of this to the public. It reached 100 million users in two months. Instagram took two and a half years.

In early 2025, DeepSeek — a Chinese lab — released an open-source reasoning model that rivalled the best closed models, built for under six million dollars. It wiped 600 billion off Nvidia's market cap in a day. Then GPT-5 launched with a 400,000-token context window. Claude 4 became the top coding model. Google shipped Gemini 3, scoring 100% on a maths benchmark that was considered extremely hard a year earlier.

And then a key shift happened. Up to this point, generative AI was fundamentally reactive — you ask it something, it responds. But in 2025, AI agents arrived. Not chatbots — systems that browse the web, write and run code, use tools, and complete multi-step tasks autonomously. Protocols like the Model Context Protocol emerged to standardise how agents interact with the world. The shift is from AI you talk to, to AI that plans and acts on its own.

---

**What Comes Next**

So where is this headed?

Those single agents are already evolving into swarms. Multi-agent systems where a coordinator delegates to specialists — each optimised for a specific task. Think of an ant colony. No single ant knows the big picture, but the colony solves complex problems through simple rules and coordination. Amazon already runs swarms of over a thousand robots per warehouse, coordinating in real time with no central controller.

AI is merging with the physical world. Humanoid robots are working on BMW production lines. Tesla is targeting fifty thousand robot deployments this year. The AI brain and the robotic body are finally coming together.

Then there's scientific AI — systems that don't just assist researchers but conduct science themselves. We've already seen this with AlphaFold, which solved protein folding — a fifty-year grand challenge in biology. The next step is AI that independently generates hypotheses, designs experiments, and discovers new materials or medicines.

There's also a serious challenge to the current approach. Yann LeCun — one of the godfathers of deep learning — raised a billion dollars to build "world models." His argument: large language models only understand text. They don't understand physics or causality. The next leap may require AI that simulates cause and effect, not just predicts the next word.

And perhaps the most subtle shift: AI is becoming ambient. Embedded in operating systems, in cars, in buildings, in workflows — not as a tool you open, but as intelligence woven into everything around you. AI becoming as commonplace as electricity.

As for AGI? The lab leaders are split. Anthropic's CEO says 2027. Sam Altman says by 2028, more intellectual capacity could live inside data centres than outside. Hassabis at DeepMind says fifty-fifty by end of the decade. They disagree on the timeline. None of them disagree on the direction.

---

That's the story. Seventy years from Turing's question to swarms of autonomous agents and robots on factory floors. And we're still accelerating.

This is the first in a series. In future sessions, we'll go deeper — how these models actually work, how agents and swarms are being built, and what it all means for how we write software and build products.

I've got about five minutes for questions — fire away.

---

**Word count: ~1,750**
