# data_cyborgs
Repository for data cyborgs course.

https://discourse.schoolofma.org/c/Data-Cyborgs/89
https://discord.com/channels/1372164299748802670/1372164300390793249

# case studies
- Waldrapp Project: https://www.waldrapp.eu/project-info/
- Breathing Data: https://breathing-data.multiplace.org/
- VFRAME: https://vframe.io/about/

# suggested readings/podcasts
**BOLD** indicates references that I find particularly relevant.
## weeks 1-2
- **Puttick, Alexandre. [Re/Embodied Data - Technologies of Togetherness.](https://latentspaces.zhdk.ch/datascience/re-embodied-data)**
- **The Cyborg Manifesto**
- **Intro, Chapter 1 and Chapter 6 of Ways of Being**
- Chapter 3 of Caliban and the Witch, "The Great Caliban"
- Part 1 of the Ethics of Ambiguity

## weeks 3-4
- Stalder, Felix & Savatic, Gordon. [*Infrastructure of a Migratory Bird.*](https://latentspaces.zhdk.ch/general/infrastructure-of-a-migratory-bird)
- Rettberg, Jill Walker. "Situated data analysis: A new method for analysing encoded power relationships in social media platforms and apps." Humanities and Social Sciences Communications 7.1 (2020): 1-13.
- [Wie künstliche Intelligenz bei der Aufklärung von Kriegsverbrechen hilft](https://www.spiegel.de/ausland/wie-kuenstliche-intelligenz-bei-der-aufklaerung-von-kriegsverbrechen-hilft-a-670d8c14-0b8b-42bc-a5b0-e74250cff225)
- **Podcast episode, [*A Cyborg Manifesto for Engineering Design*](https://open.spotify.com/episode/29aRZRHTU5vBczTmqkO5CJ?si=4d9eb7ada72c4219)**
- **Chapter 2 of Value sensitive design: Shaping technology with moral imagination**

## weeks 5-6
- **Puttick et al., [Shifting Paradigms: Value Sensitive Design for Fair AI Recruitment](https://github.com/arputtick/data_cyborgs/blob/main/references/VSD_Position_Paper_AIMMES_2025.pdf)**
- He et al., [Developing a Fair Online Recruitment Framework Based on Job-seekers'Fairness Concerns](https://github.com/arputtick/data_cyborgs/blob/main/references/FINDHR_VSD.pdf)
- **Beach, Michael & Fox, Tyler, [Value Sensitive Speculative Design: Exploring More-Than-Human Relations in the Age of Climate Catastrophe](https://github.com/arputtick/data_cyborgs/blob/main/references/More%20Than%20Human%20VSD.pdf)**

# homework
## week 4
Choose an entity that you would like to act as a representative for throughout the remainder of the course. It can be an individual, a community, a non-human entity or a cyborg.
Identify a specific need or value of that entity.
#### Data Assignment
1) Search for, conceptualize, or create a dataset(s) related to the entity you chose.
- Aim for data that could be used to promote/protect the need or value that you identified.
- Consider any relationships that data could create or mediate.
2) Create a folder with [YOUR_NAME]_[ENTITY_NAME] (e.g., alex_binturong) in this repository.
- create a "data" folder and upload whatever your data from 1)
- create a README.md file to keep any notes.
- EXAMPLE: https://github.com/arputtick/data_cyborgs/tree/main/alex_binturong

## week 6
Create a chatbot meant to "speak on behalf" of the entity you chose in the last assignment. The goal is to experiment with the shaping of the model's Umwelt, but these chatbots could also play a role in the speculative design phase of the course. Either as part of the design, or as co-designers.
Here are two resources for chatbot creation:
- https://huggingface.co/chat/assistants
  - Here you can create a new assistant or look at the parameter settings and system prompts for other assistants. You can tweak the model using system prompts, web links, changing parameters like temperature and top-p...
  - No coding involved.
- https://colab.research.google.com/drive/1nPOVUtKCYo4PHEVKnPLHsg4XshP-xOSF?usp=sharing
  - This is the notebook I created where you can experiment with fine-tuning the model with your own data and chatting with it.
  - Llama 3.2 requires permission to access. You can request access yourself, login with my key (posted on discourse) or use a different model (e.g., one of the versions that I already trained).
  - Llama 3.2 also works on tabular data, which could be interesting to experiment with.
  - The model requires using a GPU runtime with at least ca. 30gb of GPU memory. If you can't access one via colab, you can try running a smaller chatbot model from HuggingFace.
  - For now, the easiest way to use your own data is to upload it to the notebook server as a single file named "combined.txt".

  ## week 8
  The final two weeks of the course are devoted to whatever you want to learn about/work on. Feel free to make any requests on material you'd like to see/if you'd like to present something in class!

  In the last two classes, you practiced applying the value-sensitive design framework. If you already have your own project idea in mind, you can see if VSD can help you deepen your idea/bring it more in alignment with your values. If you don't have a project, then consider taking a feasible chunk from the ideas we came up with last week and working on that. Off the top of my head:
  - Applying girl math to/representation of trees in public funding evaluation metrics.
  - Breathing mini-game.
  - Folklore preserving AI.
  - data project on men, loneliness, mental health etc.
  - Empathy video game concept development.
  - Empathy metric/reward.


# main references
De Beauvoir, Simone. The ethics of ambiguity, tr. Citadel Press, 1962.

Federici, Silvia. Caliban and the Witch. Autonomedia, 2004.

Friedman, Batya, and David G. Hendry. Value sensitive design: Shaping technology with moral imagination. Mit Press, 2019.

Bridle, James. Ways of being: Animals, plants, machines: The search for a planetary intelligence. Penguin UK, 2022.

Haraway, Donna. "A cyborg manifesto (1985)." Cultural theory: An anthology 454 (2010).

# other references
Hildebrandt, Mireille. "Privacy as protection of the incomputable self: From agnostic to agonistic machine learning." Theoretical Inquiries in Law 20.1 (2019): 83-121.

Rouvroy, Antoinette. "Algorithmic governmentality and the death of politics." Green European Journal (2020).
