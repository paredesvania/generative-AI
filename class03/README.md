# 21 OCT

## Notes: The 35 Year History of ChatGPT

The video's main point is that ChatGPT didn't come out of nowhere. Researchers spent about 35 years on one simple task: **predicting the next word (or letter)**. Doing that with bigger and bigger networks made them learn language, and even concepts, without anyone teaching them.

Before this, neural networks could only do one thing each (spam detection, image recognition...). To make them more general, they first had to learn to "talk". In 1986 Jordan added a kind of memory to a network (an RNN) and trained it by hiding the next symbol and making it guess. Later, Elman fed a network letters with no spaces and it figured out where words start and end by itself. It also grouped words by meaning, for example animals together and food together. Chomsky said this shouldn't be possible.

In 2011 Hinton and Sutskever trained a much bigger network and it wrote text that made some sense, but it got lost after a few words. Then OpenAI trained one on Amazon reviews, and one single neuron ended up tracking whether a review was positive or negative. Nobody asked it to do that. It just appeared from learning to predict text.

RNNs have limited memory, so with long texts they lose the thread. The solution in 2017 was the **transformer**, which uses **self-attention**. Every word looks at all the other words to understand its context. For example, in "the river has a steep bank", *bank* looks at *river* and understands it means riverbank. Because it sees everything at once, it doesn't need memory the old way.

**The GPT models.** OpenAI used transformers for next-word prediction and just kept making them bigger. GPT-1 learned from 7,000 books, GPT-2 from a big part of the web, and GPT-3 was about 100 times bigger. With GPT-3, the most important new thing was **in-context learning**: you can teach it something new inside the prompt without changing the model itself. So basically, **the prompt is the program**.

**ChatGPT.** They trained GPT-3 with human feedback so it follows instructions and talks like an assistant, and that became ChatGPT. People discovered that adding "think step by step" to a prompt makes the answers better. After that came tools and agents, where the model can use other programs and systems. Karpathy compares an LLM to the kernel of a new operating system, with the context window working like RAM.

**The big debate.** Is it really thinking? Chomsky says it's "glorified autofill". Hinton says it really understands the meaning. Some people see these models as a mirror that reflects our own thoughts. Others say that if it looks like thought, it is thought. The video ends with ELIZA, an old simple chatbot that made people feel understood even though it understood nothing.

> the line between simulating thought and actual thought is becoming ever more blurred or perhaps there is no line.
