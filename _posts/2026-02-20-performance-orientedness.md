---
layout: post
title:  "the performance-oriented mind"
published: true
---

## Origin of the Story
It's 1:35AM, which is a good time of the night to feel lost and talk to ChatGPT 5.2 about my mid-PhD crisis. Here is a simplified version of my dialogue with GPT:

me: hey, can you describe who I am?

gpt: you are a systems-minded builder with a physicist's brain. blah blah blah.

me: I don't know what to do. I want to become a better computer scientist. I am done with this week's homework and now I have to do research but it doesn't excite me as much and makes me feel wanting to work on something else.

gpt: what are you deeply interested in?

me: ml compilers.

gpt: ml compilers blah blah blah..

me: let me be honest with u. I don't even know if I'm really excited about that topic.

GPT then drops the hardest line I've ever heard from AI.

gpt: So instead of asking: "Am I excited?", ask "What problems bother me?"

me: I’m often bothered when machine learning or optimization research highlights performance gains without clearly articulating the trade-offs involved. How can I rigorously predict or model performance to make such trade-offs explicit?

Everytime I read papers and hear talks, I think about performance and tend to look at things from performance perspective. For example, at Professor Wang's talk on FHE schemes for DNN, Andre asked him about possible performance degradation from using FHE and Prof. Wang said maybe yeah. I am deeply curious about methodologies in analytical modeling as well as empirical modeling. Honestly, I am also glad because this falls under the category of Andre's research.

## How Do I Model Performance?

Roofline model[^1] is a simplified, visual model of performance used to quickly determine whether a program is bound by *memory bandwidth* or *arithmetic bandwidth*.

## References

[^1]: [What is the roofline model? by Modal]( https://modal.com/gpu-glossary/perf/roofline-model )

