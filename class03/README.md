# 21 OCT

## Notes: The 35 Year History of ChatGPT

The video's main point is that ChatGPT didn't come out of nowhere. Researchers spent about 35 years on one simple task: **predicting the next word (or letter)**. Doing that with bigger and bigger networks made them learn language, and even concepts, without anyone teaching them.

Before this, neural networks could only do one thing each (spam detection, image recognition...). To make them more general, they first had to learn to "talk". In 1986 Jordan added a kind of memory to a network (an RNN) and trained it by hiding the next symbol and making it guess. Later, Elman fed a network letters with no spaces and it figured out where words start and end by itself. It also grouped words by meaning, for example animals together and food together. Chomsky said this shouldn't be possible.

In 2011 Hinton and Sutskever trained a much bigger network and it wrote text that made some sense, but it got lost after a few words. Then OpenAI trained one on Amazon reviews, and one single neuron ended up tracking whether a review was positive or negative. Nobody asked it to do that. It just appeared from learning to predict text.

RNNs have limited memory, so with long texts they lose the thread. The solution in 2017 was the **transformer**, which uses **self-attention**. Every word looks at all the other words to understand its context. For example, in "the river has a steep bank", *bank* looks at *river* and understands it means riverbank. Because it sees everything at once, it doesn't need memory the old way.

**The GPT models.** OpenAI used transformers for next-word prediction and just kept making them bigger. GPT-1 learned from 7,000 books, GPT-2 from a big part of the web, and GPT-3 was about 100 times bigger. With GPT-3, the most important new thing was **in-context learning**: you can teach it something new inside the prompt without changing the model itself. So basically, **the prompt is the program**.

**ChatGPT.** They trained GPT-3 with human feedback so it follows instructions and talks like an assistant, and that became ChatGPT. People discovered that adding "think step by step" to a prompt makes the answers better. After that came tools and agents, where the model can use other programs and systems. Karpathy compares an LLM to the kernel of a new operating system, with the context window working like RAM.

Is it really thinking? Chomsky says it's "glorified autofill". Hinton says it really understands the meaning. Some people see these models as a mirror that reflects our own thoughts. Others say that if it looks like thought, it is thought. The video ends with ELIZA, an old simple chatbot that made people feel understood even though it understood nothing.

> the line between simulating thought and actual thought is becoming even more blurred or perhaps there is no line.

## AI & ART

What do we consider ART?

**A cultural category:** Arthur Danto introduced "artworld", two visual identical objects may have different meanings when one is presented as an artwork and the other everyday object.

To understand the work as art, we need to consider its historical moment, the artist intention, and other points. Viewers interpret it through their own cultural experiences and expectations

**As an antenna:** Marshall McLuhan described art as a kind of early-warning system, or radar, for changes brought about new media. 

### So how do we know when something is art? its...

* context and history
* recognition and interpretation
* artist intention and research
* relationship with the audience and institution


* What tech is used?
* how does the artist interact with the machine?
* why do we consider it art?
* What themes and questions do the artworks explore?

1. Gordon Pask — Musicolour (1953)
* Technical system: Cybernetics, adaptive systems and feedback loops. An electromechanical system that turns sound into light.
* Human–machine relationship: A conversation. The performer plays, the machine responds with light, and the performer adapts in turn. The machine learns from the performer and extends their expressive range.
* Artistic context: It is art because it is a performance work that explores real-time interaction and creates effects the artist could not achieve alone.
* Themes: Machine learning through dialogue, art as a loop and not a finished object, and the link to Pask’s Conversation Theory.

3. Harold Cohen — AARON (1970s onward)
* Technical system: Symbolic AI, a rule-based system.
* Human–machine relationship: Cohen translated his artistic knowledge into rules. The machine draws autonomously, but only within what he encoded. He designed a system and not an individual image.
* Artistic context: Cohen was an established painter, and AARON is the result of decades of artistic research. Authorship lies in designing the system.
* Themes: Can a machine be creative if its creativity is defined by someone else’s rules? Where does the artist’s knowledge end and the machine’s output begin?

5. Karl Sims — Genetic Images (1993)
* Technical system: Evolutionary algorithms with mutation and recombination, running on a supercomputer.
* Human–machine relationship: Collaboration with the audience. Visitors choose by standing on sensors, and the machine “breeds” the next generation. The artist does not control the final image.
* Artistic context: An interactive installation. Following Becker, art is a collective activity, and here the audience is part of the creation.
* Themes: Emergence, biology as a model for creativity, and aesthetic taste as the “selection pressure” shaping the work.

7. Obvious — Edmond de Belamy (2018)
* Technical system: A GAN (generator vs. discriminator) trained on historical portraits.
* Human–machine relationship: The collective chose the dataset and the output and presented it. The model produced the image.
* Artistic context: Its status came largely from the art world: the Christie’s sale for $432,500 and the media attention. This is Danto’s “artworld” at work, since the same image outside that context might be seen as a technical experiment.
* Themes: Authorship (the GAN code was developed by Robbie Barrat), the value and market of AI art, and what a “portrait of someone who does not exist” means.

9. Mario Klingemann — Memories of Passersby I (2018–2019)
* Technical system: Neural networks (generative AI) trained on the history of portrait painting, generating faces in real time.
* Human–machine relationship: The artist designs the system and the machine produces images autonomously and endlessly.
* Artistic context: The work is a process and not a final object. There is no definitive image, which challenges the traditional idea of a painting.
* Themes: Autonomy of the machine, identity and fictional people, art history as training data, and infinite generation.

11. Memo Akten — Deep Meditations (2018)
* Technical system: Generative neural networks (GANs) and their latent spaces.
* Human–machine relationship: The artist explores the trained model, then selects and organises the material into an audiovisual experience. He does not program each transition.
* Artistic context: It is art because of the curatorial and compositional work and the conceptual framing, a meditation on connections between things.
* Themes: Unexpected associations between unrelated subjects, and the dependence of the model on the images and categories used in training, so its “creativity” is also limited by its data.

13. Refik Anadol — Machine Hallucinations (2019)
* Technical system: Machine learning and generative models on a dataset of more than 3 million images of New York.
* Human–machine relationship: The artist curates the dataset and designs the immersive experience. The AI finds patterns and produces transformations.
* Artistic context: An immersive installation in the context of digital art and museums, presented as an interpretation of the city’s collective memory.
* Themes: Memory, perception, data as material, and the move between representation and abstraction, an artificial reading of a city’s visual archive.

15. Holly Herndon — Spawn (2018 onward)
* Technical system: A custom AI “baby” (Spawn) built with neural networks and trained on human voices, including Herndon’s, her partner Mat Dryhurst’s, and an ensemble. It was used in the album Proto (2019).
* Human–machine relationship: Collaborative and almost relational. She “raises” and trains Spawn and performs with it as a member of the ensemble, not as a mere tool.
* Artistic context: It is art because it is a musical and conceptual project that rethinks how AI is made and credited.
* Themes: Consent and ownership of the voice and training data, ethics of datasets, authorship, and human–AI co-creation.

17. Paul Trillo — Washed Out, The Hardest Part (2024)
* Technical system: Text-to-video generative AI (the video was made with OpenAI’s Sora).
* Human–machine relationship: The director writes prompts, iterates, selects and edits. The AI generates the footage, while the creative vision and the narrative structure are human.
* Artistic context: A music video recognised in the film and video world (Vimeo Staff Pick), which places it within established audiovisual practice. Its value comes from direction and editing, not just the technology. Following McLuhan, it is an “antenna” experimenting with a new medium.
* Themes: Memory, time and nostalgia, the continuous “zoom” aesthetic, the boundary between real and synthetic imagery, and the future of filmmaking.
