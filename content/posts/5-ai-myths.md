+++
title = "5 AI Myths You Should Know"
date = "2026-07-16T10:00:00+05:30"
#dateFormat = "2006-01-02" # This value can be configured for per-post date formatting
author = ""
authorTwitter = "" #do not include @
cover = "ai-myths.jpeg"
tags = ["ai", "myths", "llm"]
keywords = ["ai myths", "ai misconceptions", "llm reasoning", "agent autonomy"]
description = "A simple overview of common AI myths, including hallucinations, reasoning traces, inference cost, context windows, and agent autonomy."
showFullContent = false
readingTime = true
hideComments = false
+++

Hello everyone — this is the sixth post in my “TIL (Today I Learned)” series. Today I want to share some common myths about AI.

1. AI models hallucinate.
    - Hallucination happens when the AI model gives a wrong answer with full confidence.
    - Most models today hallucinate less than 3% because they use context from the internet, refusal calibration (saying no when they do not know the answer), and extended thinking (taking time and searching resources thoroughly before giving an answer).
2. You can watch AI think.
   - The text that appears before the actual answer is called a reasoning trace. It is provided to increase user trust.
   - While the model is working through its internal reasoning, the reasoning trace helps convey the model’s thought process.
3. Training is where the AI compute goes.
    - Training is a one-time process and does not consume all of the compute.
    - Inference plays the major role here. Every time a user prompts the model, it runs and uses compute. By the end of 2026, about two-thirds of compute is estimated to be used by inference.
4. Large context windows let you offload data.
    - Having a larger context window makes the model search for a single piece of information across the whole context.
    - It is like searching for a needle in a haystack. So, providing only the information that is actually needed is very helpful to the model.
5. AI agents can work fully autonomously.
    - The role of an AI agent is to complete the goal set by the user.
    - An AI agent can hit a dead end or continue searching in some cases, so keeping a human in the loop is very important.
 
Thanks for reading. Happy learning!
