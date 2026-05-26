---
title: "Will AI Replace Software Engineers? The Mistake Behind the Hype"
subtitle: "AI can generate code, but writing code was never the same thing as software engineering."
permalink: /will-ai-replace-software-engineers/
layout: single
date: 2026-05-26
last_modified_at: 2026-05-26
excerpt: "Will AI replace software engineers? The 2025 hype cycle confused code generation with software engineering. In 2026, companies are rediscovering the value of systems thinking, architecture, testing, security, and human judgment."
categories:
  - Computer Science Education
  - AI
  - Careers
  - Software Engineering
tags:
  - will AI replace software engineers
  - AI and software engineering jobs
  - AI coding tools
  - software engineering careers
  - computer science careers
  - AI jobs
  - software developers
  - code generation
  - systems thinking
  - CSPB
  - post baccalaureate
author_profile: false
toc: false
og_image: /assets/images/blog/will-ai-replace-software-engineers.png
og_image_alt: "Software engineering team discussing a system architecture diagram while code appears on nearby screens"
---
<figure>
  <img src="/assets/images/blog/will-ai-replace-software-engineers.png" alt="Software engineering team discussing a system architecture diagram while code appears on nearby screens">
  <figcaption>
    AI can help generate code, but software engineering still depends on architecture, testing, security, and human judgment.
  </figcaption>
</figure>

The mistake was believing that writing code was the same thing as software engineering.

That, I think, is the simplest way to answer the question many students are asking right now: will AI replace software engineers?

No. Software engineers are more than code generators.

In 2025, the hype cycle around AI coding tools was enormous. Some executives talked as if software engineers were about to become optional because AI could write code, generate tests, scaffold applications, fix bugs, and work inside an IDE faster than a human could type. Those abilities were real. The conclusion was wrong. Code generation had been confused with software engineering.

In 2026, many companies appear to be rediscovering the difference.

---

## “The model still cannot operate autonomously.” - Marc Benioff, Salesforce CEO

One of the clearest signs of that shift comes from Marc Benioff. Salesforce has been highly visible in the enterprise AI conversation, and Benioff has spoken often about agents, productivity gains, and the changing nature of software work. In late 2024 and 2025, Salesforce also became part of the broader story that AI productivity might reduce the need to keep adding software engineers. That is why his newer comments are so useful.

In an April 2026 interview, Benioff said Salesforce’s roughly 15,000 software engineers had been “hugely augmented” by AI coding tools and agents. His point, however, was almost the opposite of replacement.

> “But still, those engineers are needed. **The model still cannot operate autonomously.** We’re not at that level yet of AI, so it’s really critical, so our engineering organization’s probably 30% more productive, but I wouldn’t call it 100% more productive, and that’s why even in the top AI companies, if you go to their job boards you’ll see they’re hiring a lot of engineers.” 


A 30% productivity gain is significant. It means AI can accelerate engineering work and change how teams allocate time. It does not mean companies can replace the people who understand the system, the users, the constraints, and the consequences of getting the software wrong.  That is a very different story from saying software engineering jobs are disappearing.

---

## “Programming is not software engineering.” - Mark Russinovich, Scott Hanselman, Microsoft

Mark Russinovich, Microsoft Azure CTO, and Scott Hanselman, VP of Developer Community at Microsoft, put the distinction directly in a 2026 *Communications of the ACM* article:

> “Although AI agents are advancing rapidly, human expertise remains essential in software development. **Programming is not software engineering.** Even the most reliable systems cannot fully replace the judgment, creativity, and adaptability required to handle uncertainty, make complex decisions, and maintain security. While agents can speed up workflows and reduce manual effort, they lack the intuition to anticipate edge cases and build robust solutions. Relying too much on AI risks missing subtle bugs, architectural flaws, and vulnerabilities only skilled engineers can catch. Human oversight, critical thinking, and domain knowledge are indispensable for both correcting errors and driving innovation as technology progresses.”


Programming is part of software engineering, of course. Code, syntax, and implementation still count. But software engineering also includes understanding the problem, shaping requirements, designing architecture, modeling data, testing, deploying, monitoring, debugging, improving performance, securing systems, managing maintainability, and anticipating the long-term cost of change.

Russinovich and Hanselman describe AI agents that can produce impressive code while making mistakes experienced engineers recognize quickly: masking race conditions, duplicating logic, leaving debugging code behind, implementing hacks that satisfy narrow tests, or declaring success when significant bugs remain. AI-generated code can look finished before the software is actually correct. The real question is whether someone understands the software well enough to trust, reject, revise, test, secure, and maintain what the AI produces.

---

## “The reckless temptation of AI code generation.” - David Linthicum, InfoWorld

This is why AI coding tools can feel magical in small examples and complicated in production. A demo, a prototype, or a small script can be forgiving. Production software has users, old data, edge cases, permissions, dependencies, performance constraints, compliance obligations, security risks, strange workflows, and code shaped by years of history.

> "The applications often work, which makes this approach deceptively effective. **The demo succeeds, and, at first, the feature seems to function properly.** Everyone congratulates themselves. But then the system is deployed at scale and the cloud bill skyrockets. What used to cost $10,000 a month on AWS suddenly jumps to $300,000 or more. In the worst cases, companies face multimillion-dollar monthly cloud costs for systems that should never have been built that way in the first place.

> "AI can generate code, but it doesn’t grasp efficiency like experienced engineers do. It doesn’t prioritize cost-efficient architecture. It doesn’t instinctively avoid wasteful service calls, excessive data movement, poor caching, bad concurrency patterns, noisy database behavior, or compute-heavy nonsense that might look good in a code sample but fails in real-world use. It produces something plausible. However, it doesn’t deliver something financially responsible." - InfoWorld


AI is very good at producing plausible code inside a narrow context. That can be extremely useful for boilerplate, first-pass tests, API examples, framework translation, and getting unstuck. But production code carries history that is rarely visible in a prompt. An ugly function may handle a rare customer case from three years ago. A duplicate-looking validation check may exist because two systems use the same field differently. A complicated database query may be protecting a reporting workflow the obvious version would quietly break. Good engineers learn to ask those questions before they “clean up” code that already carries production history.

---

## AI makes syntax cheaper. It makes judgment more valuable.

> "Programming is writing code. You take an idea and translate it into syntax that the compiler accepts. Software engineering is much more. It is the work of building software that works in the real world and keeps working for years. It includes programming, but also understanding the problem, writing the requirements, designing the system, choosing the right abstractions, testing, deployment, monitoring, security, and talking with stakeholders.
>
>....
>
> AI tools are very good at the first part. They write code. They do not do the second part." - Simon Martinelli  

There is a useful way to think about what AI coding tools are doing: they are making syntax cheaper. When code is cheaper to produce, more people can experiment, developers can move faster, students can test ideas more quickly, and teams can automate tedious work. That is real progress, and students should learn to use these tools well.

The harder questions move into the foreground. If AI can generate five possible implementations in a few seconds, which one fits the architecture? Which one handles the edge cases? Which one is secure? Which one will still make sense to the next developer? Which one should not be built at all? A student who understands algorithms, data structures, databases, computer systems, testing, security, and software design can evaluate AI output more carefully. A student whose only skill is asking an AI for code may get something that runs without having a reliable way to judge whether it is good software.

---



## "We are going to need tons and tons of software developers who know how to build systems, who know how to think about solving problems for customers." - Matt Garman, CEO, Amazon Web Services, May 20, 2026

The future, in Matt Garman's view, is about engineers who can build systems and solve problems for customers. If your only skill is producing syntax, AI is a direct threat. If your skill is understanding systems, customers, tradeoffs, data, reliability, and architecture, AI becomes a tool inside a larger engineering process.

Students should learn AI coding tools as accelerators inside that larger craft. The goal is to become the person who can decide what should be built, how it should work, whether the generated code is trustworthy, and how the whole system will survive contact with real users.

---
## "We're at a beginning, not an end, of software development." - Eira May, Stack Overflow blog

> "We're at a beginning, not an end, of software development. As our [Stack Overflow] CEO put it, 'There's literally an infinite number of things to build.' That’s what we’re excited about: The scale and ambition of what we can build is soaring. Barriers to entry have fallen; imagination has become reality. Developers can meet the moment just as they met historical platform shifts, from the internet to cloud computing and the rise of SaaS to mobile-first development. There's so much more to build. Let's get to work. " - Eira May, Stack Overflow, quoting CEO Prashanth Chandrasekar.

> “Cloud computing didn’t lead companies to need less compute. It made them build more things that consumed compute. AI-assisted coding may be doing something similar for software itself.” - Matt Asay, InfoWorld

That pattern should sound familiar. When cloud computing made computing resources easier to use, companies built more software that used more compute. When high-level programming languages made software easier to write, the world built more software. AI may follow a similar pattern. If software becomes easier to produce, companies may automate more workflows, create more internal tools, modernize more legacy systems, and build more AI-enabled products that previously sat in the backlog.

---


## What this means for computer science students

For current and prospective computer science students, the takeaway is straightforward. Learn the AI tools, because they are becoming part of professional software development. But treat them as accelerators, not replacements for the foundations: algorithms, systems, databases, networks, APIs, testing, security, and deployment. 

So should students still study computer science if AI can write code? My answer is yes, but they should study it with AI in view.

That is especially relevant for post-baccalaureate students. Many CSPB students come to computer science with another degree, another profession, or another way of understanding the world. In the AI era, that prior background may become part of the advantage. The strongest future developers may be people who understand computing and something else.

---



<hr>

<h3>External Sources</h3>

<ul>
  <li>
    <a href="https://www.salesforceben.com/ai-cant-replace-software-engineers-yet-marc-benioff-says/">
      AI Can’t Replace Software Engineers Yet, Marc Benioff Says
    </a><br>
    Henry Martin, Salesforce Ben, April 9, 2026.
  </li>

  <li>
    <a href="https://cacm.acm.org/opinion/redefining-the-software-engineering-profession-for-ai/">
      Redefining the Software Engineering Profession for AI
    </a><br>
    Mark Russinovich and Scott Hanselman, Communications of the ACM, April 2026.
  </li>

  <li>
    <a href="https://www.infoworld.com/article/4154587/the-reckless-temptation-of-ai-code-generation.html">
      The Reckless Temptation of AI Code Generation
    </a><br>
    David Linthicum, InfoWorld, April 7, 2026.
  </li>

  <li>
    <a href="https://martinelli.ch/ai-writes-code-engineers-build-software/">
      AI Writes Code. Engineers Build Software.
    </a><br>
    Simon Martinelli, May 13, 2026.
  </li>

  <li>
    <a href="https://timesofindia.indiatimes.com/technology/tech-news/aws-ceo-matt-garman-just-told-engineers-we-will-need-tons-and-tons-of-software-developers-who-know-how-to-/articleshow/131210917.cms">
      Amazon Web Services CEO Matt Garman just told engineers: We will need tons and tons of software developers
    </a><br>
    Times of India, May 20, 2026.
  </li>

  <li>
    <a href="https://stackoverflow.blog/2026/02/09/why-demand-for-code-is-infinite-how-ai-creates-more-developer-jobs/">
      Why Demand for Code Is Infinite: How AI Creates More Developer Jobs
    </a><br>
    Eira May, Stack Overflow Blog, February 9, 2026.
  </li>

  <li>
    <a href="https://www.infoworld.com/article/4151572/the-starkly-uneven-reality-of-enterprise-ai-adoption.html">
      The Starkly Uneven Reality of Enterprise AI Adoption
    </a><br>
    Matt Asay, InfoWorld, March 30, 2026.
  </li>
</ul>

<hr>

<h3>Related Articles</h3>

<p>If you are thinking about computer science careers, AI, and what students should be learning now, these pieces connect closely to this discussion.</p>

<ul>
  <li>
    <a href="/computer-science-jobs-2026-turning-up-again/">
      Computer Science Jobs in 2026: Are Software Engineer Job Postings Rising Again?
    </a><br>
    A data-driven look at software engineering jobs in 2026, whether postings are beginning to recover, and what AI skill demand means for students.
  </li>

  <li>
    <a href="/programming-after-programmers/">
      Programming After Programmers
    </a><br>
    A response to the New York Times Magazine article on AI and coding, with a focus on why systems thinking and domain knowledge remain central.
  </li>

  <li>
    <a href="/cu-boulder-cspb-alumni-outcomes/">
      CU Boulder CSPB Alumni Outcomes
    </a><br>
    A LinkedIn-based look at CSPB alumni roles, industries, employers, and geography.
  </li>

  <li>
    <a href="/cspb-career-changers/">
      CSPB Career Changers: How Alumni Move Into Computing
    </a><br>
    A closer look at prior degrees, previous fields, first technical roles, and career movement among CSPB alumni.
  </li>

  <li>
    <a href="/career-change-computer-science/">
      Career Change into Computer Science
    </a><br>
    A practical look at what it takes to move into software and build a strong foundation in the field.
  </li>

  <li>
    <a href="/cspb/what-you-learn/">
      What You Learn in Computer Science
    </a><br>
    An overview of the core ideas behind software systems, and why those ideas remain central in an AI-heavy environment.
  </li>
</ul>
