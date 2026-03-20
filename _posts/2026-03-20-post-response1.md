---
title: "Response 1"
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

Upon asking the model to continue with “give some context,” the model began to search external sources of data, attempting to make connections with the data it had already obtained. In the following screenshot, we see the model’s process of elimination, from unrelated sources like Yu-Gi-Oh and Dragon City, eventually settling on the works of J.K. Rowling. This shows the way LLMs, without proper context, can lead the reader down a false interpretative path before finally arriving at a true interpretation.

This leads us to the important realization: visualizations, without proper context, cannot fully be relied upon as a means of interpretation, lest the interpretation itself becomes incorrect.

![Sources1](/rlac/assets/images/source_review.png)
Sources finding

The LLM seemed to have struggled with fan fiction which didn’t have Harry Potter or the author’s name in the title – it couldn’t really pinpoint where they came from or what they were about. We can see it started with unrelated cartoons like Yu-Gi-Oh and to some video games like Dragon City, however, it gradually provides research about JK Rowling titles. I believe this last part led it to the right findings.

![Sources2](/rlac/assets/images/source_review_part2.png)
Sources findings part 2

Once the LLM was able to identify both texts correctly, it was able to provide a more meaningful interpretation of the image. It described how vocabulary was used differently in both canonical works and fan fiction, and even made some inferences about my research focus. This was where the image was more informative, not because it had changed, but because context had been established.

This is similar to research on misleading visualizations, which states that “charts do not need to be badly designed to be misleading.” The Visualization Design Lab states that misleading charts are often “faithfully plotted,” but misleading due to “framing” and “context.” When there is a lack of important context, such as sources and explanations, people will rely on their own assumptions to interpret what they see.

![GeminiResponse2](/rlac/assets/images/gemini_response2.png)
Gemini 2nd repsonse

I then tested Claude Sonnet 4.6 using word clouds, again, with no context and with instructions not to use external sources. Despite these constraints, the model correctly identified the corpus as Harry Potter fan fiction. This was surprising, as I had deliberately removed obvious identifiers.

![CludeReponse1](/rlac/assets/images/claude_response1.png)
Claude response

![ClaudeResponse2](/rlac/assets/images/claude_response2.png)
Claude response 2nd part

As with the previous model, this one also just interpreted the graphs the way they are, it looked at them and pointed out what it saw, so this seems to be the general way the LLMs are trained to respond to this type of request with limited data. But one thing did surprise me. When I was giving the LLM the data I was very careful to make sure that I crop any clues of what the texts were from the images and I was sure to tell the AI not to use any outside resources for context. But somehow above all this the LLM knew that the data was related to Harry Potter Fan fiction. When asked about the way it arrived at the conclusion, the model replied that it used clusters of character names and domain-related words like ‘Harry,’ ‘Draco,’ ‘Hogwarts,’ ‘wand’. This proves that, even though not explicitly provided, the context may have been available in the data itself.

This, of course, makes the question of whether the visuals actually speak on their own a more complex one.
The answer remains the same: no, but visuals may carry latent contextual signals that trained systems can recognize.

```
Great question! I didn't use any external resources — the identification came entirely from clues visible within the three figures themselves. Here's the reasoning:
Character Names as Evidence
The most decisive clue was the co-occurrence of multiple highly specific names that belong to the same fictional universe:
Harry, Hermione, Ron, Ginny, Draco, Malfoy, Voldemort, Luna, Dumbledore, Snape, McGonagall, Hagrid, Sirius, Lupin, Dobby, Lockhart, Weasley, Slytherin
No single name is conclusive on its own, but this exact cluster of names is uniquely associated with the Harry Potter series. The probability of all these names appearing together in any other context is essentially zero.
Supporting Vocabulary
Beyond names, specific world-building terms reinforced the identification:
wand, spell, castle, hogwarts, potions, slytherin, eaters (as in "Death Eaters")
These are setting-specific words that don't appear together outside of Harry Potter contexts.
The "Draco" Signal
The name Draco is particularly telling. It is an extremely rare first name in general usage, and its repeated pairing with Harry, Hermione, and wand in thousands of contexts makes the source unambiguous. The wildcard search term draco* (with an asterisk) capturing 2,368 contexts further signals this is a large dedicated corpus, consistent with fan fiction archives.​
Fan Fiction Indicators
Finally, certain words signaled fan fiction specifically rather than the original books:
chapter appearing as a high-frequency word (authors addressing readers between chapters)
text and phone collocating with Draco (modern AU settings impossible in canon)
The presence of original character names like Mudiwa, Freja, and Adonis in Figure 2
—
Overall, this experiment proved that visualizations are not standalone tools for understanding. Both humans and LLMs use context, either supplied or understood, to interpret them. Although LLMs can use context to interpret a visualization, they are not always able to do so correctly and can provide false information.

This suggests that when using visualization in academic writing, it is very important to provide LLMs with carefully curated context.
```

# Additional Research 

## Although not part of the main analysis, I briefly explored an additional tool.

I was talking to my friend about the different AIs available and which was best for what and he recommended I try a browser by Perplexity called “Comet”. The browser is AI powered which allows it to analyze and interact with the data that is on the screen on its own. I decided to play a bit with it and opened my homework and let the AI analyze it.

The instructions I had given it were to use the interactive graph 1 and give me some new findings. 

![Comet1](/rlac/assets/images/comet_response.png)
Comet response

At first it was playing with the graph and how it was displayed until it figured out it could add new data and remove the old one which it did in the end.

![Comet2](/rlac/assets/images/comet_response3.png)
Comet response part 2

In the end it removed the words “wand” and “Voldemort” and decided to explore the main antagonist and protagonist Draco and Harry which I found quite interesting and it even gave me new findings based on that data. This is both fascinating and honestly scary as I was able to observe the AI clicking on my screen and getting data without me inputting it. I also tried asking it to interpret all the graphs without looking at the text but it cheated and just summarized the whole page for me so I decided not to include that data.
