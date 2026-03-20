---
title: "Assignment 1"
excerpt_seperator: ""
categories:
    - Responses
---

To explore the relationship between context, visualization, and interpretation, I revisited the visualizations I created for Assignment 1 and tested how different large language models would interpret them when given different levels of context. Specifically, I used Perplexity Pro which gave me access to Gemini 3.1 Pro and Claude Sonnet 4.6. My goal was to understand whether visualizations can indeed “speak for themselves,” and how both humans and LLMs construct meaning from them.
Through this process, I try to argue that visualizations cannot speak on their own. Instead, both humans and LLMs are heavily dependent on context to interpret them. Without context, interpretations are highly speculative, or even misleading. However, LLMs can sometimes reconstruct context based on learned associations, which complicates the assumption that interpretation is purely visual.

I started off by giving the line graph (with the words ‘spell,’ ‘flying,’ and ‘invisible’ tracked) to the Gemini 3.1 Pro without any additional context. As can be seen in the screenshot, the model was able to correctly describe the structure and trends of the given graph but did not provide further interpretation. This demonstrates that, without context, LLMs tend to focus on descriptive reading rather than analytical interpretation.

It is worth noting, however, that even without much context, the LLM was able to make an interpretation that the texts were most likely from the Harry Potter series based on the partial labels and patterns.This indicates that interpretation is not purely derived from the visual itself, but also from patterns embedded in the model’s training data.

![GeminiResponse1](/rlac/assets/images/gemini_response1.png)
Screenshot of the response
