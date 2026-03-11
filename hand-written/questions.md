# Possible Questions

## What is the difference between "The Imitation Game" and "The Turing Test"?
"The Imitation Game" is "The Turing Test". Alan Turing called it "The Imitation Game" but people nowadays mostly refer to it as "The Turing Test".

## What is reinforcement learning?
Reinforcement learning is a type of machine learning. There is
- supervised learning (labeled data, spam filter - spam or not spam)
- unsupervised learning (unlabeled, purchase data - these users purchase similar things)
- reinforcement learning (reward signal — good or bad — AlphaGo)
- generative AI (creates new content — can use any of the above to learn).

## What is Reinforcement Learning from Human Feedback (RLHF)?
Reinforcement Learning from Human Feedback is RL where the reward signal comes from human preferences rather than an objective measure. A human ranks outputs and the model learns to produce outputs the human prefers. Anthropic's Constitutional AI replaces most of the human feedback with AI feedback guided by written principles.

## What is the difference between a cost function and reward function?
A reward function is associated with reinforcement learning where the output only gets a 'score' for how well it did. A cost function (the opposite of a reward function) is mostly used in supervised learning which uses labeled data and thus has a correct output.

## How similar is AI to how our brains work?
Neural networks were inspired by the brain, but it's a loose inspiration. The brain uses electrochemical signals, not matrix multiplication. Interestingly, researchers are now finding that some things AI does, like attention in Transformers, have unexpected parallels in how the brain actually works.

## What connection do the Expert Systems have to what we think of today as AI?
No direct technical lineage to neural networks, but the ideas around knowledge representation and explainability live on. Many modern systems are hybrids — rules plus machine learning together.

## I would be interested, now that we have those agents, do you see our job as SWEs in danger? [PLANTED]
In its current state, I would not see our jobs as SWEs in danger. Why?
But honestly, I don't know. There is a lot of hype and uncertainty.

## There was this plateauing issue but then they started getting better again, why?
They introduced reasoning and trained on long-horizon persistence, tool use, and self-recovery.

## What sort of patterns could the perceptron learn?
The perceptron learned to identify cards punched on the left and cards marked on the right for example. It was very basic.

## What is scaling?

Scaling is increasing
- the model size (the number of parameters) 
- the amount of data the model is trained on
- the compute

## Isn't compute just dependent on the model size and dataset size?

No, compute is about how long or how intensely you train the model which determines the values of the models weights.

## What is an agent?

An agent is AI that can carry out tasks. It is no longer a chat bot and has access to tools for example for editing a file. An agent can also work autonomously to some degree not just carrying out the task you ask it to do but other related tasks too. For example, a coding agent could delete files not longer needed after performing a task.

## Does all of Deep Learning use Neural Networks?
Yes, Deep Learning is neural networks. Neural networks with many layers that is.

## What is a Convolutional Neural Network?
CNNs are neural networks with a sliding filter used to process the data.

## What types of ML are there?
Three types, categorised by how they learn:
- Supervised learning: the AI gets the correct answer provided by a human and learns to copy it.
- Unsupervised learning: the AI gets no answers and figures out patterns for itself, like categorisation.
- Reinforcement learning: the AI tries things, gets a reward signal (good or bad), and learns to do better. No correct answer given.

Generative AI (creates new content — text, images, code) is not a fourth type — it can use any of the above to learn.

## How many layers does a neural network have to have to be considered a deep learning neural network?
There is no strict consensus. The most common definition is at least 2 hidden layers, but in practice modern deep networks have hundreds of layers so the exact cutoff doesn't really matter.

## What is Reinforcement Learning with Verifiable Rewards (RLVR)?
Reinforcement Learning with Verifiable Rewards. That is reinforcement learning where the learning comes from outcomes that can be checked like code passing tests for example.

## What made the models so much better at the end of 2025?
Karpathy "most capability progress in 2025 was defined by labs chewing through the overhang of this new [RLVR] stage — similar sized LLMs but a lot longer RL runs."

## Why couldn't they just add more layers to the perceptron in the early years to get better results?
There was no way to update the models weights beyond the output layer at the beginning and even when backpropagation existed compute was an issue and there was less interest in these techniques.

## What is a neural network?
A neural network is a network of nodes loosely inspired by the connection of neurons in the brain. Its nonlinearity allows it to deal with more complex problems.

## Are any Expert Systems still used today?
Yes, but most of them are a mix of rule-based and machine learning techniques. For example there is the WHO disease diagnosis systems.

## What does GPT stand for?
Generative Pre-trained Transformer

## What was the difference between transformers made?

"The animal didn't cross the street because it was too tired."                          
                                          
What does "it" refer to? The animal. Attention learns to give "animal" a high weight when processing "it", and "street" a low weight. That's all attention is — learned relevance weights between words.

## Is the transformer architecture used in image models like DALL-E?
Yes, but in the modern models it is used to understand the prompt and diffusion models are used to generate the image.

## Who recognizes the potential for scaling based on the Attention is all you need paper?
It was OpenAI.
