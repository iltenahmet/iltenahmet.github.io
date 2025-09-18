+++
title = "Coding with AI"
date = 2025-04-13
template = "page.html"
+++

Since joining an [AI company](https://theterminalx.com/) recently, I've had the opportunity to reflect on my use of AI when programming.

<!-- more -->

When ChatGPT emerged in late 2022, as a junior Computer Science student in college, I was mind-blown by its capabilities. For that semester, I fully embraced the AI hype train, believing anyone not using this tool was falling behind and destined to become a relic of the pre-GPT world. This enthusiasm lasted until the end of the semester when my grades hit their lowest point, I learned very little, and my projects were full of bugs I had no idea how to fix.

I painfully realized that when you rely too heavily on AI-generated code, debugging becomes a nightmare. You lose crucial context about your own code and often incorporate snippets with non-obvious issues that become problematic as projects scale.

After that experience, I restricted myself to using AI only for occasional syntax help, fearing deeper usage would lead to the same confusion and dependency. This cautious approach continued until I developed interest in AI agents and began building small projects. Working with applications that leveraged LLMs helped me understand these systems—their capabilities and limitations. During this period, the following [video](https://youtu.be/7xTGNNLPyMI?si=-g7g8SxFWrfO8RIC) by Andrej Karpathy explaining how LLMs work was particularly illuminating.

This coincided with the release of Deepseek R1 and the emergence of more reasoning-focused models. LLMs are essentially powerful statistical token generators, but I always thought they are just that, and fundamentally incapable simulating human-like cause-effect reasoning. I still believe what reasoning models do differs from genuine human reasoning, but they come way closer than what I thought was possible. To me, reasoning models seem to address most common pitfalls of standard AI models.

Since joining a company building AI agents, where using AI is actively encouraged, I've observed some patterns to get optimal results from LLMs, both in personal use and in our agent development.

Currently, I've established some personal guidelines that help me leverage AI when programming without falling into previous traps:

1. Context Is King: Your primary job when working with AI is managing context. With the right context, it produces wonders; with the wrong context, it inevitably hallucinates. This critical filtering and provision of relevant context remains fundamentally human-driven.

2. Keep Completions Short: I rarely request completions longer than 15 lines of code. Longer snippets give AI room to insert unrequested elements and take more time to fully understand. With lengthy AI-generated code, I risk losing important context and failing to grasp what's happening in my own code. This makes debugging extremely difficult and often introduces subtle bugs that emerge later—the worst kind. Instead, I request small snippets and review each before integration.

3. Going to AI for Help Should Be Intentional: I avoid using AI directly in my IDE except for trivial completions. I prefer making LLM queries a deliberate activity where I consider the codebase and carefully select appropriate context—relevant files, functions related to the problem, relevant documentation, etc. This approach reduces irrelevant answers and helps me reason more effectively about AI responses.

Besides these, my current setup includes a browser tab with [openrouter.ai](https://openrouter.ai/)'s chatroom interface to easily switch between recent models within a single chat. I typically use Deepseek R1 for non-obvious tasks—waiting up to a minute for complex queries is acceptable. For boilerplate or simple tasks, I use Claude 3.7 with "thinking" mode set to self-moderated for faster responses.

I almost always enable web search functionality to use AI as a search tool, which I found often yields better results than directly searching on a search engine.

These guidelines are personal, and reflects my current thinking, though I'm still learning and the field is rapidly evolving.
