---
title: "AI for Poets (or Poets for AI)"
layout: single
permalink: /speaker-series/ai-for-poets-or-poets-for-ai/
excerpt: "Ben Snyder (AWS) discusses how creative thinkers and interdisciplinary backgrounds are shaping the future of AI and software development."
toc: false
toc_label: "Contents"
toc_icon: "list"
---
![Ben Snyder, Senior Applied Scientist at Amazon Web Services, CSPB Speaker Series talk "AI for Poets" at CU Boulder]
(/assets/images/speaker-series/ai-for-poets/ben-snyder.jpg)

In February we hosted **Ben Snyder**, Senior Applied Scientist at Amazon Web Services, for a talk in the CSPB Speaker Series titled *AI for Poets (or Poets for AI)*.

Ben discussed why creative thinkers and people with interdisciplinary backgrounds may play an increasingly important role in the future of software development and AI systems.

{: .notice--info}
This page contains a lightly edited transcript of the CSPB Speaker Series talk  
**AI for Poets (or Poets for AI)** by Ben Snyder (AWS).


# AI for Poets (or Poets for AI)
## Why Creative Thinkers and Eclectic Backgrounds Will Shape the Future of Software

> **CSPB Speaker Series**  
> Post-Baccalaureate B.S. in Applied Computer Science  
> University of Colorado Boulder

---

> ### Speaker Highlight
> **Ben Snyder** is a Senior Applied Scientist in Prototyping at Amazon Web Services. He earned degrees in sociology from the University of Oklahoma and Harvard University, then completed a master's in computer engineering at Boston University. His work has included forecasting and risk modeling at Capital One, distributed systems for large-scale AI training across thousands of GPUs, and rapid prototyping of AI systems across robotics, manufacturing, logistics, and agriculture.

> ### Talk Focus
> This talk explores Ben Snyder's nonlinear path from sociology into AI, the current AI tooling landscape, the strengths and limitations of modern models, and why interdisciplinary thinkers may be especially well positioned to shape the future of software.

---

## Table of Contents

- [Event Introduction](#event-introduction)
- [Opening Remarks](#opening-remarks)
- [A Nonlinear Path into AI](#a-nonlinear-path-into-ai)
- [From Sociology to Machine Learning](#from-sociology-to-machine-learning)
- [Professional Background and Applied AI Work](#professional-background-and-applied-ai-work)
- [Why Interdisciplinary Backgrounds Matter](#why-interdisciplinary-backgrounds-matter)
- [Statistics, Social Science, and AI](#statistics-social-science-and-ai)
- [Research Methods, Graphs, and Human Feedback](#research-methods-graphs-and-human-feedback)
- [Changing Gears: Where AI Works Best](#changing-gears-where-ai-works-best)
- [Medicine, Law, Forecasting, and Robotics](#medicine-law-forecasting-and-robotics)
- [Autonomous Vehicles, Education, and the Limits of Hype](#autonomous-vehicles-education-and-the-limits-of-hype)
- [Smaller Models, Statistics, and System Design](#smaller-models-statistics-and-system-design)
- [Technical Overview of Modern AI Models](#technical-overview-of-modern-ai-models)
- [Agents, Coding Tools, and the Renaissance Developer](#agents-coding-tools-and-the-renaissance-developer)
- [Social Consequences and Responsible AI](#social-consequences-and-responsible-ai)
- [Resources and Closing](#resources-and-closing)
- [Q&A](#qa)
  - [Will some AI use cases return to manual processes?](#will-some-ai-use-cases-return-to-manual-processes)
  - [How will larger context windows develop?](#how-will-larger-context-windows-develop)
  - [How would Ben teach coding now?](#how-would-ben-teach-coding-now)
  - [What about junior engineers and the job market?](#what-about-junior-engineers-and-the-job-market)
- [Final Thanks](#final-thanks)

---

## Event Introduction
{: .notice--info}
**Curry Guinn**  
Associate Director of Student Experience  
CU Boulder Applied Computer Science Post-Baccalaureate Program

Good afternoon everyone, and welcome to today's CSPB Speaker Series event. The title of today's talk is **AI for Poets, or Poets for AI**.

We are very pleased to welcome **Ben Snyder**, a Senior Applied Scientist at Amazon Web Services.

Ben's career path has been anything but linear. He began in sociology and earned degrees from the University of Oklahoma and Harvard University, then completed a master's in computer engineering at Boston University.

Professionally, he has worked in forecasting and risk modeling at Capital One. He has helped design distributed systems for large-scale AI training using thousands of GPUs. Today, he focuses on rapid prototyping of AI systems across a range of industries and applications, including robotics, manufacturing, logistics, and agriculture.

In this talk, Ben explores why diverse backgrounds and creative thinking are going to become increasingly essential in the age of AI.

Please join me in welcoming Ben Snyder.

---

## Opening Remarks

{: .notice--primary}
**Ben Snyder (AWS)**  
Senior Applied Scientist, Amazon Web Services

Thanks, Curry. Let me just share my screen here and make sure this all works correctly.

I have three monitors going so I can see everyone, keep my notes open, and show the slides without anything exploding in the wrong direction.

Thank you again, Curry.

I am Ben Snyder, a Senior Applied Scientist with AWS. What I want to go over today is my journey from sociology into AI systems, and then I want to dig into where I think a lot of AI work is heading.

I also want to talk about the current tools and some of the models. We are going to get a little into the technical details of how some of these models work, and I want to show a few of the tools we use, just to give everyone an idea of where the industry is, where it is going, and why unusual backgrounds can actually be an asset in this kind of work.

I will spend about forty minutes on the main presentation. Feel free to jump in with questions at any time, and I will also leave some time at the end so we can have a conversation.

---

## A Nonlinear Path into AI

I started out at the University of Oklahoma studying sociology. Honestly, I went into college without a clear idea of what I wanted to study and thought sociology sounded interesting.

I approached it from a quantitative angle. I did a lot of work in social network analysis, not social networks like Facebook, but graph theory and demographics. My first published paper looked at how social ties affected remittances for migrants in rural Thailand. Even though it was in the social sciences, there was still a very quantitative side to it.

I started a PhD at Harvard, got partway through, completed my master's, and then realized that while the field was interesting, it was not where I wanted to spend the long run of my career.

That was when I shifted into computer engineering through Boston University's **LEAP** program, the Late Entry Accelerated Program.

> **Pull Quote**  
> *My path into AI was not linear. It moved from sociology to statistics-heavy research to computer engineering, and that combination turned out to be far more useful than I expected.*

---

## From Sociology to Machine Learning

The LEAP program is designed for people who did not study engineering as undergraduates. You come in with a prior degree, fill in the gaps with one or two semesters of undergraduate coursework, and if you maintain the required GPA, you are automatically admitted into the master's program at BU.

When I found it, I was still at Harvard and realized BU was right across the river. That is one advantage of Boston. There are universities everywhere.

At that point I did not even know I would end up in machine learning or AI. I just saw that computer engineering connected well to statistics and looked like a good direction. As I got deeper into the program, I began to see that I could leverage the sociology background with the engineering training and turn that into large-scale statistics and machine learning.

The LEAP program was incredibly valuable for making that transition. It emphasized coming in with the background you already had and figuring out how to use it rather than discarding it.

---

## Professional Background and Applied AI Work

Before AWS, I worked at Capital One doing forecasting for credit cards. This was mostly risk modeling and pure statistics. We were trying to forecast how people would use their credit cards under different economic conditions.

You find all kinds of strange but predictive behavior in that kind of work. It turns out you can make a surprising number of predictions from things like what fast food places people go to.

From there, I joined AWS, originally on the SageMaker team. SageMaker is Amazon's managed AI and machine learning platform for training and deploying models. Specifically, I worked in distributed training performance. The question was: given AWS infrastructure, how fast can we train the models customers want to train across large numbers of GPUs?

That involved work with GPUs and, more recently, Amazon's custom AI accelerators, Trainium. It also meant a lot of work with **EFA**, Amazon's networking system, which functions a bit like InfiniBand. The latest version can push extremely high throughput between instances, and you need that kind of speed for AI training because you have to move information quickly across machines. Using systems like NCCL, we can effectively reach into GPUs across the data center and grab data straight from memory.

A lot of the work was very low-level: figuring out how to make distributed training run as fast as possible.

In one project we got Mask R-CNN, an object detection model, down to about six minutes of training time from a more typical twelve hours. At that point the number is almost absurd and starts to function as marketing, but the real point is utilization. For large language models like T5, the real goal is to get the highest possible GPU utilization so training is cost-effective.

More recently I moved into prototyping within AWS. Instead of helping customers use existing AWS products, our team works with customers who have unusual use cases that do not fit standard off-the-shelf solutions.

Some examples:

- **AI-powered video search** for a company that provides data for autonomous vehicles. They wanted to describe a scene on the road and retrieve the relevant video segments for training systems.
- **Protein structure prediction** at scales beyond what was readily available in standard AlphaFold workflows.
- **Agricultural drones** with limited edge hardware that needed to learn scenes while flying. We built a model distillation loop where the edge device sent data to the cloud, which used large models and zero-shot detectors to analyze it, generate new training sets, retrain, and redeploy.
- **Robotics prototypes** including work with a Boston Dynamics Spot robot that could respond to natural language commands such as dancing or changing its battery.

What we do is work with customers on these unusual prototypes and then identify which parts can be generalized and reused elsewhere.

---

## Why Interdisciplinary Backgrounds Matter

How does all of this connect back to sociology?

First, sociology is often much more quantitative than people expect, especially in areas like social network analysis and demographics. There is a lot of statistics underneath that work, and those skills transfer surprisingly well into AI and machine learning.

Second, sociologists have spent a century working with messy data, and machine learning is full of messy data.

That jump from sociology to AI turned out to be easier than many people assume. What really matters is that interdisciplinary backgrounds often give you tools that people who moved straight through a conventional path do not have.

In my case, sociology brought a kind of econometric and social-data-oriented statistical perspective that ended up being very meaningful in AI.

And this is true across fields, not just sociology.

- If you come from literature, that can be valuable in NLP research. Large language models are trained on enormous amounts of text, and understanding language deeply matters.
- If you come from biology, that matters in protein folding, molecular modeling, and other areas where domain understanding is essential.
- If you come from design, psychology, or education, you may be especially well prepared to think about how humans actually use these systems.

> **Pull Quote**  
> *A unique background is not something you have to overcome in AI. Very often, it is the thing that gives you an edge.*

---

## Statistics, Social Science, and AI

There is a joke that statistics is like hanging one picture frame on a wall, machine learning is hanging another over it, and AI is hanging a third over that. It is all still built on similar foundations, just at a larger and more layered scale.

Under the hood, an LLM is still probability theory and statistics. Neural networks and LLMs are, in a real sense, regression models with more layers and more complexity.

What I often see in people who went straight through computer science is that they understand neural networks at a high level, but when you dig into why they behave a certain way, they sometimes lack the deeper statistical tools needed to reason about them.

That is where starting from statistics can be so helpful.

Many familiar ideas from sociology and social science show up again in AI:

- causal inference
- variance explained
- overfitting
- generalization

In sociology, if you add too many terms to a regression, you overfit. In AI, the models are vastly over-parameterized, and if you train too long or structure things poorly, you overfit in a different way. But conceptually the problem is similar. You end up with a model that fits the training data too narrowly rather than learning something broadly useful.

That kind of background is very useful when you are trying to understand why a model is showing the behavior it is showing.

---

## Research Methods, Graphs, and Human Feedback

Social network analysis has become especially useful recently because of the growth of **graph neural networks** and graph-based transformer models.

For example, I recently worked on fraud detection in payment transactions. For a long time, the standard was **XGBoost**, a tree-based model that banks have relied on for years.

More recently, there has been growing evidence that transformer-based models can outperform XGBoost in some of these scenarios, especially when they can explicitly model the graph-based relationships between merchants, consumers, and transactions.

Stripe recently published work showing that when you construct that payment ecosystem as a graph and feed it into the model, fraud detection performance can improve dramatically.

This is exactly the kind of case where ideas from social network analysis transfer naturally into AI.

At the same time, this all comes back to data and messy data. Social science has long experience dealing with that.

One example from work we are doing now involves a continuously learning model based on human feedback. This gets into reinforcement learning with human feedback, where a model interacts with a person who says whether a response is correct or incorrect.

That requires building the right human feedback loop, which in practice means building a good survey. Sociology turns out to be useful there too.

When you learn survey design, you learn to keep things short and usable. If someone has to answer five pages of questions to get airport Wi-Fi, they will click random answers just to move on. That gives you bad data. In contrast, one or two focused questions can give you cleaner feedback.

Understanding how people actually interact with data collection systems matters if you want the data to be useful.

Finally, qualitative data also matters. We often focus on quantitative metrics, but qualitative judgment is still essential.

If I am training an object detection model, I do not just want the metric. I want to look at the outputs and see whether the bounding boxes are going where I expect. There may be something wrong with the score itself.

One of the most memorable things from a qualitative methods course in sociology was reading *On the Origin of Species*. It is one of the great scientific works, and it is fundamentally observational and qualitative. It is built on careful attention to what is actually happening in the world.

You need the quantitative side, but you also need the ability to step back and make informed qualitative judgments.

---

## Changing Gears: Where AI Works Best

At this point in the talk, I wanted to shift gears and talk more directly about where AI is actually strong and where people sometimes get swept up in hype.

I would say AI is strongest in areas where it produces **verifiable solutions**.

Protein folding is one of the best examples. You are dealing with an enormous search space, essentially an almost infinite set of possible folds, and trying to find a low-energy structure. Traditional supercomputing approaches can take a long time.

With systems like AlphaFold, AI can narrow that huge space down to a much smaller number of plausible solutions. Maybe most of those are still wrong, but if one is right, that is incredibly valuable. A human can then come in and verify whether the candidate structure makes sense.

That pattern is important. AI often works best when it reduces a huge solution space and then hands something verifiable to a human expert.

> **Pull Quote**  
> *AI is often at its strongest when it narrows the space of possible answers and lets a human verify what matters.*

---

## Medicine, Law, Forecasting, and Robotics

Protein folding was one of the real success stories of AI and was part of the work recognized by the Nobel Prize in 2024. It has had major implications for drug discovery, which is why we get a lot of requests from companies wanting to use AI in that space.

Medical imaging and diagnostics are also promising. AI systems can help flag scans that deserve closer review, or surface diagnoses a doctor may not have initially considered. The human expert remains essential, but the model can help reduce the search space and point attention in useful directions.

Personalized medicine also has huge potential. With developments like mRNA vaccines, there is growing interest in custom treatments for individual patients. There was work from Moderna, for example, looking at using AI to help rapidly develop personalized solutions for specific cancers.

Another area is the legal profession. AI can be extremely useful for navigating enormous document collections. Traditional search works at the word or phrase level, and older embedding methods can help somewhat, but if you want to search for a concept across a massive legal corpus, models like BERT or T5 can do that much more effectively.

Forecasting and anomaly detection are changing too. When I was at Capital One, we experimented with neural networks and did not get much value out of them. More recently, some transformer-based models have started to outperform older approaches in certain settings.

That said, **XGBoost** is still extremely powerful. It remains hard to beat, and one reason is that it is so easy to use. You can throw reasonably structured data at it and it often just works. Transformer-based models can outperform it in some cases, but they usually require much more work in tuning, data preparation, and architecture selection.

In robotics and industrial automation, we are seeing **vision-language-action models** become important. These use architectures related to LLMs, but they are grounded in physical environments.

Instead of programming every robotic motion directly, you can tell a system something like, "pick up the ball and put it in the plate," and the model figures out the sequence of movements. In some warehouse and factory settings, these kinds of systems are also useful for richer safety logic. Instead of hard-coding a simplistic rule like "if you see a person, stop," which can be triggered by a photo on a box, the model can make a more context-sensitive judgment about what is actually happening in the environment.

The underlying architecture has a lot in common with what powers LLMs. The difference is in the inputs and outputs.

---

## Autonomous Vehicles, Education, and the Limits of Hype

Autonomous vehicles are clearly coming, but they are arriving much more slowly than many people predicted.

The reason is that autonomous driving is a **safety-critical** problem. This is very different from a setting where a model can generate candidate answers and a human can verify them. The whole point of autonomous vehicles is to remove the human from the loop, and that means the required reliability threshold is much higher.

Waymo and similar systems are impressive. I rode in a Waymo recently and it was remarkable. But fully removing human supervision is much harder than many people thought ten years ago, when people were predicting consumer cars without steering wheels by 2017.

That never happened, and the reason is simple: getting the last level of reliability is extraordinarily difficult.

A useful rule of thumb is that AI tends to see earlier success where outputs can be verified and later success where reliability must be guaranteed in unconstrained real-world settings.

Education is another area where I think the promise is enormous, but the risks and challenges are equally real.

As the son of a family of teachers, this one really matters to me.

There are incredible opportunities. The other day I asked Claude to explain a difficult statistical concept I had struggled with in grad school. It walked me through it with a series of quizzes and a code-building progression, and by the end it was genuinely one of the best explanations I had ever gotten.

There is a Steve Jobs line about computers being bicycles for the mind. I think AI has the potential to extend that idea.

At the same time, we are all seeing stories of students using AI to cheat and offload their thinking rather than deepen it.

That means education is a place where interdisciplinary expertise matters enormously. We need people who understand education, psychology, and how both children and adults learn, so we can design systems that help rather than erode learning.

---

## Smaller Models, Statistics, and System Design

When people hear "AI," they often think only of large language models like GPT, Claude, or Gemini. But AI is a much broader field and has been around for decades.

There is still a huge role for smaller, specialized models.

Models like Mask R-CNN, YOLO, or vision-language-action systems are not LLMs. They are often smaller, edge-deployable, and highly task-specific. They run on constrained hardware and solve narrower problems.

In many real systems, what we actually need is not one giant model that understands everything. We need **small models and large models working together**.

For example, with a drone at the edge, a smaller action model may need to handle local perception and response, while a cloud-based larger model handles planning, training, or richer contextual reasoning. Figuring out how those pieces interact is less about code syntax and more about understanding the environment, the user, and the system requirements.

Traditional statistics also still matters a great deal.

If you ask a large language model to compute something simple like a mean, it may confidently give you the wrong answer. On my team we sometimes joke that LLMs are like angsty teenagers. They often just want to give you a response that will make you go away.

So if you are working with real-world forecasting, trends, cycles, or structured decision processes, you still need classical statistical and machine learning tools. You need to understand who is coming into the grocery store, what they buy, what the seasonal patterns are, and how those trends evolve over time.

Even as LLMs improve, they remain poor at many of those tasks unless they are embedded in a larger system that includes more reliable tools.

You also have to think about failure modes, who benefits, who gets harmed, and how long implementation really takes. Early in my engineering career, I had the habit of telling my manager that something would take two weeks or four weeks. In reality, it almost always took at least three times longer than I thought.

That turns out to be a good rule in AI too. Many things are harder and slower than the hype suggests.

---

## Technical Overview of Modern AI Models

I moved quickly through this part in the live talk because I wanted to preserve time for questions, but I wanted to include the basic technical outline here.

### Convolutional Neural Networks

These are models used for image understanding and object detection. We use models like **YOLO** a lot in vehicle-related work because they are fast and effective.

### Large Language Models and Attention

LLMs are transformer-decoder models, and at the core is the concept of **attention**.

This grew out of work in machine translation. Earlier recurrent neural networks had to encode a sentence into a bottleneck representation and then decode it into another language. Attention changed that by allowing the decoder to look back at what parts of the input mattered most at each step.

Then the 2017 paper **"Attention Is All You Need"** showed that the attention mechanism itself, plus positional information, could outperform those older recurrent approaches.

From there, people realized you could train decoder-only transformer models on enormous amounts of text and get something like GPT, a model designed to predict the next token based on previous tokens.

Scale that up to billions or trillions of parameters and you get models that can perform forms of reasoning and language understanding that would have seemed astonishing not long ago.

### Encoder Models

Not all transformer models are decoder-only LLMs. Encoder models still matter, especially for tasks like sentiment analysis, summarization, and classification.

### CLIP and Multimodal Learning

One important encoder-based idea is **CLIP**, where you encode both images and text and train the system to match them correctly. If you do that across a massive image-text corpus, you get a model that can understand images in relation to language.

A lot of image generation systems are effectively using the inverse of that same basic relationship.

---

## Agents, Coding Tools, and the Renaissance Developer

AI agents are another major theme in current AI discussions.

In simple terms, an AI agent is usually some combination of:

- an LLM
- a system prompt
- a set of tools

The difference from a normal chatbot is that the agent can actually *do things*. It can run commands, use software, interact with a browser, contact other systems, escalate to a supervisor, or carry out workflows on a computer.

This is the logic behind many coding assistants and automation systems.

One mechanism for doing this is the **Model Context Protocol**, where you can effectively attach tools to the model so it can do more than just generate text.

I also briefly showed **Kiro**, Amazon's AI coding tool.

These systems have become extremely capable. At this point, I probably write only about five percent of the code I use directly. I hear people say all the code is AI-generated, and I would not quite go that far, but ninety-five percent or more in many workflows is absolutely plausible.

That does **not** mean coding knowledge is obsolete.

A recent example: I was training a contrastive loss model similar to CLIP. My training loss was going down, but validation accuracy was collapsing to zero, which is the opposite of what should happen. It turned out the coding assistant had flipped two terms in the loss function. The code looked plausible, but it was wrong.

I only found it because I knew what the loss function was supposed to be doing.

That leads to what Werner Vogels has described as the **Renaissance Developer**. The next generation of developers cannot just be coders. They need to understand the technology, the application domain, and the human setting in which the system will be used.

This is part of what makes the current moment exciting for me. I can come up with an idea and have a working implementation in a day or less. That lets me focus more on the idea itself, the design of the system, and the value of the application.

But that makes domain knowledge, judgment, and interdisciplinary perspective even more important.

> **Pull Quote**  
> *The job is shifting from writing every line of code to figuring out what should be built, how it should work, and what actually matters in the system.*

I showed one example of a robot arm responding to human input over video. We put together a prototype in about twenty minutes. It was not finished and still needed debugging, but even just a year earlier that would likely have taken weeks.

That is why the nature of software development is changing. The bottleneck is moving away from raw code production and toward problem framing, evaluation, debugging, and domain understanding.

---

## Social Consequences and Responsible AI

At the end of the talk, I wanted to emphasize that domain knowledge is not only useful for building AI systems. It is also essential for building them responsibly.

For protein folding, the key specialist on our team has a PhD in biology. For other projects, we rely on specialists in engineering, the social sciences, and other fields who understand what the system is really doing in context.

We also need to think about the social consequences of AI.

A ProPublica article I often send people covered a police department that implemented an AI prediction system for recidivism. As you might guess, the system produced deeply problematic outputs, effectively encoding racist assumptions into predictions of future violent crime.

That is exactly why we need people who understand not only what a model can do technically, but also what its outputs mean socially and ethically.

The same applies in education. We need people who understand how students learn and how systems affect them. More broadly, we need to ask:

- How do people actually use this?
- What are the economic consequences?
- What are the social consequences?
- What is the model learning from the historical data we feed it?

Because with LLMs in particular, we are training on vast portions of human history. What those models absorb from that is an extremely important question.

---

## Resources and Closing

I ended the talk by sharing a few resources:

- **Werner Vogels' talk** on the Renaissance Developer, which goes deeper into many of the same ideas
- **Dive into Deep Learning**, a free online textbook with code examples
- **SageMaker Studio Lab**, a free JupyterLab environment with access to GPUs
- **My LinkedIn profile**, where people could connect and ask for more resources

The main takeaway is straightforward:

We need people with unusual backgrounds. We need people with broad intellectual range. We need people who understand how these systems will actually work in the world and how to develop them responsibly.

---

## Q&A

### Will some AI use cases return to manual processes?

A student asked whether, given the amount of QA and human-in-the-loop work many startups are still finding necessary, we may see a return to manual processes in some areas where people are trying to use AI today.

Ben's answer was yes, at least in part.

He said there is definitely an AI bubble and a lot of hype. Some companies are implementing AI and finding it does not work for them, sometimes because AI is not the right solution, and sometimes because they are using the wrong kind of AI.

A common mistake is to throw a large language model at every problem. When that fails, people conclude AI does not work, when in reality they may have needed a different model class altogether.

He expects some pushback in the next few years and thinks some jobs may return in areas people assumed would be automated immediately. In many cases the issue is not that automation is impossible, but that the timeline is much longer than companies expected.

He also referenced an MIT study from the middle of last year suggesting that a very high percentage of AI implementations fail in production. Even so, he noted that for a new technology, even a small percentage of successful implementations can still be very significant.

### How will larger context windows develop?

Another question asked how Ben sees the progression toward larger context windows and broader system awareness.

He noted that his team had recently published a larger-context model on Hugging Face. When people talk about context length, they mean the number of input tokens an LLM can handle before it starts losing track of earlier material.

Today many major models operate somewhere in the range of a few hundred thousand tokens up to roughly a million. Extending that further is an active area of work.

He suggested that some of the progress will likely come from newer architectures, especially **state space models** or hybrid systems that combine state space models with transformers, since they do not have the same computational constraints on long context.

He also emphasized that progress will come from broader modalities. Right now multimodal often means text and image, sometimes video. In the next few years, he expects much more work on models that can understand environments, graph data, and other structured representations.

He also pointed to a finding from GPT-4 era work: training on both images and text improved text performance too, because image understanding gave the model richer conceptual grounding.

His view is that as models gain longer context and broader modalities, we are likely to see another significant jump in capability.

### How would Ben teach coding now?

Another question asked how Ben would teach coding today.

He said he would still begin with something like a difficult C++ course, because even if most people end up working primarily in Python, they still need to understand what is happening under the hood. Concepts like pointers, memory behavior, and low-level system behavior matter even if you do not interact with them every day.

At the same time, he thinks we now need courses on what he jokingly called **vibe coding**. Students need to learn not only how to code, but how to prompt, debug, and work effectively with AI coding tools.

He showed that in his own IDE he had a set of design documents for guiding the coding assistant, some generated partially by the assistant and then edited by him. His point was that effective use of AI coding tools requires understanding how the model thinks and how to structure prompts so it produces what you actually need.

If he were designing a course now, he would likely include assignments where students use LLMs to generate code, then debug, refine, and reason about that code in a principled way.

### What about junior engineers and the job market?

A final major question asked how AI is affecting the job market for junior engineers.

Ben said the concern is very legitimate. A lot of junior engineering work traditionally involved producing boilerplate code, and AI tools are increasingly capable of doing that.

Even so, he emphasized that the work is not disappearing so much as shifting.

He noted that teams are still hiring, including at AWS, because the need remains. What changes is what people are valued for.

He stressed several things:

- Knowing how to work with AI coding tools is itself a skill
- Prompting and debugging matter
- Understanding model behavior matters
- Projects matter more than ever

If you can show that you came up with an idea, built a system, used AI tools appropriately, and delivered something end-to-end, that is very compelling.

He gave the example of someone recently hired who came from biology and had built visualization tools for cell analysis. What mattered was not just the code, but the demonstration of problem-solving, tool use, and real project execution.

He was also blunt about the current hiring process. In his view, the system is a mess because people are using AI to submit enormous numbers of applications, and AI is also being used to screen them. That makes the pipeline frustrating for everyone.

As a result, networking matters even more. Job fairs, recruiter conversations, and making sure real humans see your work may be more effective than blindly submitting applications online.

---

## Final Thanks

After the questions, Curry thanked Ben for the talk and for taking the time to speak with the group.

Ben said he was happy to answer questions through LinkedIn and had more resources he could share.

Elisabeth Stade encouraged students to keep the conversation going in Piazza across their courses, including cognitive science and software development, and to use the talk as a starting point for further discussion.

Ben closed by saying he always enjoys talking about this material and is excited when people want to learn more.

{: .notice--info}
**Related Post**

Reflections on this talk:  
[Why AI Needs Poets →](/ai-for-poets-reflection/)