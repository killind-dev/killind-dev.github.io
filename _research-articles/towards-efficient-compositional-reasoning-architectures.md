---
layout: research
title: "RL-1: Towards More Efficient Compositional Reasoning Architectures"
date: 2024-02-17
authors: ["Kiran Illindala", "Mihir Chintawar"]
affiliations: "Random Labs"

sections:
  - title: "Background"
footnotes:
  - id: "1"
    text: "This is the first footnote."
references:
  - id: "1"
    text: "Author Name, Article Title, Journal, Year."
---

Composition itself can be essentially described as reasoning over abstract directed graphs of varying sparsity. We can formulate the task difficulty as proportional to the number of edges. In learning to generalize across graphs, we posit that language models trained using Next Token Prediction approximate rulesets that would in fact generate the most probable graphs ([1](#background)).

## Background

To understand why compositional reasoning is important, and therefore why this research is valuable, it's necessary to take a step back and recognize that essentially everything that exists is of some sort of compositional reasoning.

When you take a look at a scene, theres some amount of automatic segmentation that occurs which allows you to recognize an object. Even if the scene is quantized at the resolution of your retinal cell density. This is relevant for two reasons: 1) it means that what you percieve as continuous is actually quantized, and 2) what is percieved as continuous is 
