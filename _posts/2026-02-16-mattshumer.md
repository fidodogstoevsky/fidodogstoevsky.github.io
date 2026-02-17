---
layout: post
title: PANIC! TERROR! DREAD! Ok, NOW will you give me your money?
subtitle: Response to Matt Shumer's "Something Big Is Happening"
cover-img: /assets/img/amazingstories.jpg
thumbnail-img: /assets/img/amz.jpg
share-img: /assets/img/amazingstories.jpg
tags: [AI, LLMs]
author: Gidon Kaminer
---

# Response to Matt Shumer article

[This](https://shumer.dev/something-big-is-happening) article [has](https://www.businessinsider.com/matt-shumer-something-big-is-happening-essay-ai-disruption-2026-2) been [making](https://www.ndtv.com/feature/ai-could-replace-50-of-entry-level-white-collar-jobs-within-5-years-warns-tech-ceo-10989453) the [rounds](https://www.inc.com/justin-bariso/ai-founder-viral-5000-word-post-ai-bigger-than-covid-change-the-world-what-you-need-to-know/91301159). It's a compelling sci fi short story that would be right at home in a 50s pulp mag. Unfortunately it's been read by over 100 million people (supposedly)


+ "deliberate choice", intelligence explosion

no, it's just good at coding because it's a restricted domain and there's github sourcecode to scrape

the tasks are well defined

with code, you can run it to verify if it works. So the AI can verify by itself whether it works or not. can't do this with open questions

they're salivating at the prospect of AI making genuine discoveries to accelerate AI, they jump on things like AI discovering new proofs etc, but none of these are actually new

+ what happened in software will happen to everything

no, because software is a restricted domain. there's no github for all white collar work


+ it has "taste", "judgement" - just an aggregate of others' tastes

+ claude code is impressive, the models are so much better now

the thing that's revolutionary is the harness, the pipelines, the way the models are orchestrated. this is all meta to the models themselves, it's built to check itself

they wanna think that the models themselves are actually getting exponentially better, but right now it's still the same LLM tech, just slightly better models, the improvements are in how they're used



He argues that AI labs purposefully started by training their models 

> The AI labs made a deliberate choice. They focused on making AI great at writing code first... because building AI requires a lot of code. If AI can write that code, it can help build the next version of itself. A smarter version, which writes better code, which builds an even smarter version. Making AI great at coding was the strategy that unlocks everything else. That's why they did it first.




### text

Shumer begins along the lines of "You didn't think covid would be world-altering and then it was. Similarly, you don't think AI will be a world-altering, but it will be." He doesn't actually look into why 



> Each new model wasn't just better than the last... it was better by a wider margin, and the time between new model releases was shorter.


He tries to sell February 5th as an abrupt leap 

> Then, on February 5th, two major AI labs released new models on the same day: GPT-5.3 Codex from OpenAI, and Opus 4.6 from Anthropic 

His "example" isn't much of an example. What "app" is he talking about? 

> Let me give you an example so you can understand what this actually looks like in practice. I'll tell the AI: "I want to build this app. Here's what it should do, here's roughly what it should look like. Figure out the user flow, the design, all of it." And it does.


Of course it has "taste", 

> But it was the model that was released last week (GPT-5.3 Codex) that shook me the most. It wasn't just executing my instructions. It was making intelligent decisions. It had something that felt, for the first time, like judgment. Like taste. The inexplicable sense of knowing what the right call is that people always said AI would never have. 

This is one of the most eggregious fabrications. He argues that AI labs purposefully started by training their models on code so that 

> The AI labs made a deliberate choice. They focused on making AI great at writing code first... because building AI requires a lot of code. If AI can write that code, it can help build the next version of itself. A smarter version, which writes better code, which builds an even smarter version. Making AI great at coding was the strategy that unlocks everything else. That's why they did it first.

Software developers think that every other job is just software but in a different domain of expertise. 

> The experience that tech workers have had over the past year, of watching AI go from "helpful tool" to "does my job better than I do", is the experience everyone else is about to have. Law, finance, medicine, accounting, consulting, writing, design, analysis, customer service.

It's plateauing 

> The models available today are unrecognizable from what existed even six months ago. The debate about whether AI is "really getting better" or "hitting a wall" — which has been going on for over a year — is over. It's done.

He's using it because he's salivating at the prospect of not needing to pay employees

> One of them, the managing partner at a large firm, spends hours every day using AI. He told me it's like having a team of associates available instantly. He's not using it because it's a toy. He's using it because it works.

It still can't "do" arithmetic. It doesn't actually calculate

> In 2022, AI couldn't do basic arithmetic reliably. It would confidently tell you that 7 × 8 = 54

Doesn't actually explain the [METR](https://arxiv.org/pdf/2503.14499) metric. He's just excited about this because of the doubling

> About a year ago, the answer was roughly ten minutes. Then it was an hour. Then several hours. The most recent measurement (Claude Opus 4.5, from November) showed the AI completing tasks that take a human expert nearly five hours. And that number is doubling approximately every seven months, with recent data suggesting it may be accelerating to as fast as every four months.

Baby doubling

> If you extend the trend (and it's held for years with no sign of flattening) we're looking at AI that can work independently for days within the next year. Weeks within two. Month-long projects within three.

First of all, just because LLMs can access relevant data and combine them towards the task at hand doesn't mean it's smarter than PhDs.

Second of all, yeah it can't do office jobs if all it can do is regurgitating that stuff

> Let that land for a second. If AI is smarter than most PhDs, do you really think it can't do most office jobs?


Come on, are we really just gonna take these people at face value? They have a financial stake in convincing people that the intelligence explosion is coming

> This isn't a prediction about what might happen someday. This is OpenAI telling you, right now, that the AI they just released was used to create itself. 

> Dario Amodei, the CEO of Anthropic, says AI is now writing "much of the code" at his company, and that the feedback loop between current AI and next-generation AI is "gathering steam month by month." He says we may be "only 1–2 years away from a point where the current generation of AI autonomously builds the next."

> Each generation helps build the next, which is smarter, which builds the next faster, which is smarter still. The researchers call this an intelligence explosion. And the people who would know — the ones building it — believe the process has already started.



Moltbook security vulnerabilities, vibe coded mess

These new models certainly have impressive capabilities, they can execute tasks much more autonomously, they can iterate, it's not just sitting there and prompting through a maddening conversation with a chatbot "please fix this bug". 

But these impressive capabilities are not a sign of a quantum leap in the models themselves. The core technology of LLMs hasn't fundamentally changed in the last few years. Rather, companies are packaging LLMs in architectures for iterating, dicking around with files, etc. It's an engineering pipeline

it's the harness


### Background: Matt Shumer is a con-artist

In writing this I wanted to engage with the points made in the article itself, rather than resort to ad hominem character attacks. But now that I've gone through the text, I'm at liberty to say that Matt Shumer is a charlatan who should be ignored. 

For starters, Matt Shumer has a vested interest in the proliferation of AI in white collar work. He's the CEO of an [AI company](https://www.hyperwriteai.com/) whose main product is an AI writing assistant. His market isn't software developers, it's office workers at large. He has a product to sell them. He needs to convince them that his product is Claude Code but for all white collar work. Which, for reasons discussed above, it is not and cannot be. ### MORE


Additionally, Matt Shumer is widely known in the AI community as a [prolific liar and scammer]([](https://venturebeat.com/ai/reflection-70b-model-maker-breaks-silence-amid-fraud-accusations)). In September 2024 he released a model called [Reflection 70B](https://reflection70b.com/), which he claimed was "hallucination-free" and "the world's top open-source model". He credited these advancements to a supposedly innovative "Reflection-Tuning" technology wherein the model works aloud through its thought process and corrects its mistakes. Along with the model, he published statistics indicating world-class performance on evaluative benchmarks. 

It didn't take long for people to download Reflection, run the tests themselves, and find that its [performance was actually worse](https://venturebeat.com/ai/new-open-source-ai-leader-reflection-70bs-performance-questioned-accused-of-fraud) than Meta's Llama 3.1 70B, the open-source model it was built upon. Shumer attributed the performance discrepancy to "something got fucked up during the upload process", promised to release the supposedly corrected model but never actually did. 

trained on benchmark data to optimize for benchmarks

just a Claude Sonnet-3.5 wrapper with a lazy filter to remove "Claude" from answers

Why was Shumer so desperate to [generate hype](https://venturebeat.com/ai/meet-the-new-most-powerful-open-source-ai-model-in-the-world-hyperwrites-reflection-70b)


was an investor in now defunct [GlaiveAI](https://glaive.ai/), attributed the success of his model to the AI generated datasets they provide

This guy isn't even in it for the long con. He's just looking to cash out as quickly as possible. And if that means fabricating performance metrics to inflate the value of a company he owns stock in, he will do that. 