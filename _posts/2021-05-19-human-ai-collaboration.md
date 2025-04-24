---
layout: post
title: How Science Fiction Inspires Human-AI Collaboration
summary: AI shines best when it's collaborating with humans.<br>Originally published on the <a href="https://engineering.cresta.com/posts/human-ai-collaboration">Cresta Engineering Blog.</a>
publish_date: May 19, 2021
tags: sci-fi ai cresta

---

![Experts on Day One](/assets/scifi-1.jpeg)
*Illustrations by Gary Yankovich*

Artificial intelligence is often imagined as a foil to human life. How do the astronauts in 2001: A Space Odyssey proceed when their ship’s operating system turns against them? What happens when Ava in Ex Machina defeats her creator and escapes into the world?

These popular depictions of sentience thrive on the tension between humans and our seemingly ungovernable inventions. But while these existential narratives captivate our present, it is science fiction’s less discussed moments that illuminate the future.

## AI as Advisor, Instead of Decider

Rather than giving AI an adversarial role, the most magnetic storylines — and those which inform the human-AI systems deployed at Cresta — place AI in an advisory role.

In Asimov’s fictional world, scientists in Foundation map out the future using mathematical probabilities. As AI, behind the veil, is no more than a long series of mathematical computations, you can imagine this capability as an AI fortune-teller with uncanny accuracy.

But what is most striking about Asimov’s story lies not in the prophetic technology, but that the ultimate decision power of what to do in light of the technology’s truths rests with humanity. AI can tell you that the empire is going to collapse, but it is up to humans to decide how to proceed.

![Suggestions](/assets/scifi-2.jpeg)
*Suggestions: AI helps users figure out what to say next.*

Similarly at Cresta, AI serves as an advisor, instead of a decider. Our product injects confidence and empathy into every conversation across a contact center. At each of the millions of natural language messages streaming in every day, agents are given suggestions of what an expert might say next. Our AI models (fine-tuned on BERT and GPT-2) generate paths a conversation can take and highlight those promising optimal conversion and customer satisfaction. Human agents, armed with realtime expertise, are empowered to shape the conversation on their own terms.

## Simplifying the State of the World

The vision of “AI as advisor” has prompted us to rethink every human touchpoint in our machine learning pipeline. From data annotation to qualitative analysis, manual tasks can be open-ended and costly. How can we simplify the state of the world before it reaches human eyes?

To accelerate data annotation, our Dynamic Labeling system takes advantage of AI as an advisor. Annotators first input a few examples of a label. Then, our model searches tens of thousands of chats to find semantically similar messages, which the human annotator can accept or reject.

Instead of painstakingly hunting down examples in a chaotic chatspace, annotators can find a handful and let AI bubble up the rest. While the model suggests what to label, the annotator decides how to label.


![Dynamic Labeling](/assets/scifi-3.jpeg)
*Dynamic Labeling: AI figures out which messages matter most.*

Chatspace Clustering is another step in our modeling pipeline benefiting from AI’s advisory role. Out of a customer’s millions of chats, which are the most important to look at? Where are the most salient examples of agent expertise; what are the most common reasons visitors chat in?

To answer these questions, we use unsupervised learning to initially structure a customer’s chatspace. The state of the world is reduced from a million to a few hundred key chats, achieved without any human effort and presented to a conversation analyst, who can understand the chatspace by only looking at select representative chats. AI organizes the world, and humans make sense of it.

![Chatspace Clustering](/assets/scifi-4.jpeg)
*Chatspace Clustering: AI categorizes millions of messages, freeing up thousands of hours users once spent sifting through chats.*

AI’s recurring advisory role recalls another seminal piece of science fiction. In Dune, Mentats are cognitively advanced humans who can perform computer-like calculations. As artificial intelligence is merely a stream of computations stretching to infinity, Mentats bear the closest resemblance to AI in Herbert’s world. With their talent of finding insights from large amounts of data, they serve as political advisors to the ruling class — inspiring the consultative role of Cresta’s AI in production today.

## Tomorrow's Human-AI Systems

You might be wondering: if AI knows what an expert would do, why can’t it just be the decider and send the “correct” message automatically? The answer is that it can and it should. In certain contexts, such as collecting customer information, processing payment details, and troubleshooting common problems, AI falls more naturally into a decider role. These ritualistic tasks are ripe for automation, and abstracting them away allows agents to focus on the more personal elements of human interaction.

In other contexts, AI shines best in an advisory role. Scenarios inviting empathy and ambiguity — human conversation, roadmaps for the future, saving the galactic empire — are better suited for a complementary relationship. It’s not because AI isn’t smart enough. As algorithms advance and compute power multiplies, it’ll likely be the “smartest” one in the room. But even in a world without AI, many decisions rarely benefit from being made by one smart person in isolation — choices are enriched by advice, research, reflection, collaboration.

If we ask the scientists in Foundation about the human-AI systems of tomorrow, they might say AI will advise us, astound us, and animate thousands of characters in the writerly imagination — but at the end of the day, AI will do its best work when the “main character” energy belongs to its users.


<em> Thank you to Navjot Matharu, Lars Mennen, Zayd Enam, Shubham Gupta, and Chip Huyen for reading drafts, and Gary Yankovich for the illustrations. </em>

## References
- Foundation ([Asimov 1951](https://en.wikipedia.org/wiki/Foundation_(Asimov_novel)))
- BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding ([Devlin et al., 2018](https://arxiv.org/pdf/1810.04805.pdf))
- Ex Machina ([Garland 2015](https://en.wikipedia.org/wiki/Ex_Machina_(film)))
- Dune ([Herbert 1965](https://en.wikipedia.org/wiki/Dune_(novel)))
- 2001: A Space Odyssey ([Kubrick 1968](https://en.wikipedia.org/wiki/2001:_A_Space_Odyssey_(film)))
- Language Models are Unsupervised Multitask Learners ([Radford et al., 2019](https://d4mucfpksywv.cloudfront.net/better-language-models/language_models_are_unsupervised_multitask_learners.pdf))




