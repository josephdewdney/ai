# The Evolution of AI — Info Chunk Script

**Target: ~10 minutes**

---

So, I've been using AI and coding agents more and more recently, as I'm sure a lot of you have been as well, and I became increasingly curious as to how we actually got here. I studied neural networks, biologically inspired optimization algorithms and the like in my mathematics degree, and I've followed the developments closely, but I didn't have the overall picture. So I did some research — with help from Daniel and Timo — and found it quite interesting and actually quite telling. We decided it would be a good topic to kick off a series of AI info chunks. In future sessions we can pick particular topics to go deeper into and perhaps pour some cold water on some of the AI hype, so keep in mind what you'd want to learn more about during this talk.

We're going to walk through a timeline, from the 1950s to where things are heading next. Let's get into it.

---

**Early Enthusiasm, Great Expectations**

So the story really starts in 1950, when Alan Turing publishes this paper — "Computing Machinery and Intelligence" — and he asks a deceptively simple question: can machines think? And rather than trying to define what thinking actually is, he sidesteps the whole thing and proposes what we now call the Turing Test. If a machine can hold a conversation and you genuinely can't tell it apart from a human, does it even matter whether it's "really" thinking? It's a clever framing, and it basically kicked off the whole field.

Then in 1956, a group of researchers got together at Dartmouth College — John McCarthy, Marvin Minsky, Claude Shannon, and a few others — and they coined the term "artificial intelligence." And they were incredibly optimistic. They genuinely believed that within a generation, machines would be able to do anything a human mind could do.

And early on, it actually looked like they might be right. In 1966, a program called ELIZA came out of MIT. It was essentially a chatbot that used pattern matching to simulate a therapist. And people were amazed by it — some genuinely believed they were talking to something that understood them. It was really the first time software created that illusion of intelligence.

Around the same time, researchers were building what's now called symbolic AI, or "Good Old-Fashioned AI." The idea was pretty straightforward — you encode human knowledge as rules. If this, then that. Expert systems took this approach and ran with it, and for narrow, well-defined problems, they actually worked quite well.

---

**A Dose of Reality**

But the thing is, these systems were brittle. They couldn't handle ambiguity, they couldn't learn from new data, and the hardware of the time just wasn't powerful enough to do anything more ambitious. So funding dried up. Twice, actually. The first AI winter hit in the mid-1970s. Interest came back in the 80s with expert systems, but when those failed to live up to the hype, a second winter followed in the late 80s and early 90s.

And I think this is worth pausing on, because there's a pattern here that repeats throughout AI history — hype, followed by reality, followed by disappointment. And I'd encourage you to keep that pattern in mind, because I think it's relevant to where we are today as well.

---

**Statistical Learning**

So what actually pulled AI out of the cold? It was really a philosophical shift more than anything. Instead of telling a computer the rules, you give it data and let it figure out the rules itself. That's machine learning.

Now, the concept of neural networks actually goes all the way back to the 1940s. And in 1957, Frank Rosenblatt built what he called the Perceptron — a simple network that could learn to classify inputs. But it was limited, and after Minsky and Papert published a book proving those limitations in 1969, interest in neural networks basically collapsed for over a decade.

The real breakthrough came in the 1980s with backpropagation — essentially a method for training multi-layer networks by working out how much each connection contributed to the error, and adjusting accordingly. So suddenly neural networks could learn much more complex patterns. But they still needed far more data and compute than was available at the time.

In the meantime though, other machine learning approaches were thriving. Support vector machines, random forests, boosting methods — these became the workhorses of practical AI through the 90s and 2000s. If you've used spam filters, recommendation engines, fraud detection — that was all machine learning, just not the deep learning variety.

---

**The Deep Learning Revolution**

And then 2012 happened. A neural network called AlexNet won the ImageNet competition by a massive margin. It used convolutional neural networks running on GPUs — and the thing is, these techniques had been around for decades. But three things had finally converged at the same time: we had the algorithms, we had the data thanks to the internet, and we had the compute thanks to GPUs that were originally designed for video games. That convergence unlocked capabilities that had been theoretically possible but practically out of reach.

And what followed was just this explosion of progress. In 2014, GANs showed that AI could generate realistic images. In 2016, AlphaGo beat the world champion at Go — and Go is a game so complex that brute-force search is essentially impossible. The system had to develop something that genuinely looked like intuition.

---

**The Foundation Model Era**

Then in 2017, a team at Google published a paper called "Attention Is All You Need," which introduced the transformer architecture. And this really did fundamentally change natural language processing. The key insight was the attention mechanism — instead of processing text word by word in sequence, the model could look at all parts of the input simultaneously and learn which parts are relevant to each other.

And this architecture turned out to be incredibly scalable. When you scaled it up, something quite unexpected happened — the models started developing capabilities that nobody had explicitly programmed. Reasoning. Code generation. Translation. Researchers call these emergent properties, and I think they're one of the most fascinating things about this whole story.

GPT-2 in 2019 showed that a large language model could generate surprisingly coherent text. GPT-3 in 2020, with 175 billion parameters, showed that scale itself was kind of an ingredient — the more you scaled, the more capabilities just emerged. And then in late 2022, ChatGPT brought all of this to the general public. It reached 100 million users in two months. For context, it took Instagram two and a half years to get there.

Now, just looking at the last year or so — in early 2025, a Chinese lab called DeepSeek released an open-source reasoning model that rivalled the best closed models, and they reportedly built it for under six million dollars. That sent shockwaves through the industry — it actually wiped 600 billion off Nvidia's market cap in a single day. Then GPT-5 launched with a 400,000-token context window, Claude 4 became the top coding model, and Google shipped Gemini 3, which scored a perfect 100% on a maths benchmark that was considered extremely difficult just a year before.

And then I think the really interesting shift happened. Up to this point, generative AI was fundamentally reactive — you ask it something, it gives you an answer. But in 2025, we started seeing proper AI agents. Not chatbots — these are systems that can browse the web, write and run code, use tools, and complete multi-step tasks pretty much autonomously. Protocols like the Model Context Protocol have emerged to standardise how these agents interact with external systems. And I think that's the key transition — it's going from AI you talk to, to AI that actually plans and acts on its own.

---

**What Comes Next**

So where does all of this go from here? Nobody really knows for certain, but there are a few directions worth watching. Agents are already evolving into swarms — coordinated multi-agent systems, a bit like ant colonies, where specialists work together on complex tasks. AI is merging with the physical world — humanoid robots are already on BMW production lines. There's scientific AI, building on AlphaFold, where systems don't just assist research but conduct it. There are people challenging the whole LLM approach with "world models" that understand physics rather than just text. And AI is becoming ambient — embedded in cars, buildings, workflows, becoming as commonplace as electricity.

As for AGI, the lab leaders disagree on timelines — anywhere from 2027 to end of the decade — but none of them disagree on the direction.

---

So that's the story. Seventy years from Turing's question to swarms of autonomous agents and robots on factory floors. And it's still accelerating.

This is the first in a series of info chunks on AI. In future sessions we'll go deeper into specific topics — how these models actually work under the hood, how agents and swarms are being built, what it means practically for how we write software and build products. So if anything from today sparked your curiosity or if there's a topic you'd want us to cover, let us know.

Right, I've got about five minutes for questions — fire away.
