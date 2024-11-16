## Background

Plant scientists and geneticists have made progress on understanding the function of several genes and corresponding proteins. This work is facilitated in part by public datasets of genomes and 
common / similar genes between plant species. Recent trends in this space include finding useful genes in 'wild relatives' of crops, cross-breeding varieties of plants to collect the best traits,
and identifying natural defenses against disease, pests, and drought.

I realized that I believed that climate change threatened the world's food supply, but I knew nothing about it. I wondered if GMOs were the next step,
and if LLMs could decode DNA. Turns out, the full story is much, much more complicated. But there is interesting research going on into biology + LLMs, and I'd like to highlight
work in plants, specifically.

## Goals

- Catalog major models and tasks related to training language models on plant genomes and proteomes
- Link to or write example code for the models being used for tasks
- Resources for embeddings / vector search / similarity to better identify new genes and proteins
- Demo tools for a less-studied crop family (quinoa / kaniwa / huazontles)

## Some Questions / Non-Goals

**Is this GMO?** No, not necessarily. Plenty of plant research is figuring out what genes are connected to parts of the cell, parts of the plant, different traits, etc. Then there
are plenty of researchers who are collecting, mapping, and crossing varieties of corn, wheat, potato, etc. including heirloom varieties and wild relatives. This info is useful for
GMO research, but it could also be used to find existing defenses to reduce chemical pesticides/herbicides or stop the spread of fungi which harm crops.

**Where is AlphaFold / protein folding?** If you are a researcher you can ask DeepMind for access to AlphaFold.
I'm not interested in listing and comparing protein folding models, because you should probably just use AlphaFold.

**What about my DNA?** Human testing and identifying human genes has its own challenges around testing / iteration and of course ethics. I don't want an amateur LLM to hallucinate
a bunch of information about your DNA. Plants and micro-organisms are complex and lively but much safer to study.

