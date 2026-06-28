+++
title = "Promptware Kill Chain"
date = "2026-06-28T10:00:00+05:30"
#dateFormat = "2006-01-02" # This value can be configured for per-post date formatting
author = ""
authorTwitter = "" #do not include @
cover = "promptware-kill-chain.jpg" # place a cover image at static/img/ or in the post bundle
tags = ["security", "promptware", "ai"]
keywords = ["promptware", "kill chain", "model security"]
description = "A short overview of the promptware kill chain: stages attackers use to inject malicious prompts or data into LLM-driven systems."
showFullContent = false
readingTime = true
hideComments = false
+++

Hello everyone — this is the second post in my “TIL (Today I Learned)” series. Today I want to share the concept of the promptware kill chain.

Like malware (malicious software) and ransomware (messages with a demand to pay), we now face promptware.

Promptware is the practice of injecting malicious or misleading information into a system that an LLM relies on.

The promptware kill chain includes the following stages:

1. Initial Access — Initial access can be obtained directly or indirectly. Direct access happens when an attacker injects malicious prompts; indirect access happens when incorrect or manipulated content (context) is added to the data the model uses.
2. Privilege Escalation — By instructing the LLM to assume certain roles or behave in ways that bypass safeguards, an attacker can cause the model to ignore constraints and perform harmful actions.
3. Reconnaissance — Attackers can probe and abuse the model's APIs, plugins, and other endpoints to discover capabilities and additional attack surfaces.
4. Persistence — Instead of relying on session-only prompts, attackers can inject malicious content into persistent data or knowledge stores. Manipulative prompts may disappear after a session, but injected data can be repeatedly referenced by the LLM and cause ongoing malicious behavior.
5. Lateral Movement — Once an attacker has a foothold, they can move laterally across other systems and software that the model can access, expanding the scope of the compromise.

A model's greatest strength — its interconnectedness — is also its greatest weakness.

Thanks for reading. Happy learning!
