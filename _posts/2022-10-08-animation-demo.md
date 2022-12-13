---
title: Animating the build of a research environment network
date: 2022-10-08 12:00
categories: [Guides]
twitter_description: "Post describing how an animated build of a research environment network was created, as part of a digitisation demonstration."
---

We demonstrated part of echinopscis at a recent event - where we were integrated with a demonstration of Kew's herbarium specimen digitisation setup.

## Aims

- High level:
    - Visualise what happens to data post digitisation
    - Demonstrate the kinds of data elements that can be used to place specimen data in context
    - Show that we are contributing to a network of data
- For hands-on specimen researchers:
    - Demonstrate digital access to specimen and literature resources

## Design

The test case genus selected was Solanum, which is comprehensively digitsed at Kew. I built a script that read the following data sources to populate a research environment:

1. Read names in Solanum from IPNI
2. For each name, search GBIF for specimens with type status and link the name to each specimen 
3. For each specimen, create or link to the holding institution
4. For each specimen, create or link to the person responsible for its collection (DarwinCore term recordedbyid)

The graph view in Obsidian was set up to differentiate between the various node types (names, specimens, institutions, people) using colour and I recorded an animation of the graph build.

Final version of the animation is available here:

<iframe src="https://player.vimeo.com/video/756415657?h=7d7fe55587" width="640" height="360" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen></iframe>

## Demonstration set-up

We also showed some hard-copy resources to show how specimens are used in evidence in scientific literature. We colour coded labels on these to link up with the digital data shown onscreen.

