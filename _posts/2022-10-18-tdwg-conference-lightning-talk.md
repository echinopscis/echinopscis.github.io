---
title: Biodiversity Information Standards lightning talk
date: 2022-10-18 12:00
categories: [Talks]
twitter_description: 'Video and annotated slide deck for lightning talk "Open science tools: Supporting hands-on creation of the \"digital extended specimen\"" from the Biodiversity Information Standards 2022 conference in Sofia, Bulgaria.'
background: "/assets/backgrounds/photo-1594803294810-c860e5d29e07.jpg"
background_alt: "Image by Ivan Nedelchev (unsplash)"
layout: slides
slides:
  - img: /assets/images/tdwg2022-ltd14/Slide1.PNG
    img_alt: "Open science tools: Supporting hands-on creation of the “digital extended specimen”"
    notes: |
      Work is a collaboration between [Nicky Nicolson](https://www.kew.org/science/our-science/people/nicky-nicolson) (NN) and [Eve Lucas](https://www.kew.org/science/our-science/people/eve-lucas) (EL) both from [Kew Science](https://www.kew.org/science)
  - img: /assets/images/tdwg2022-ltd14/Slide2.PNG
    img_alt: "Explain personal and institutional contexts"
    notes: |
      Personal context: **NN** transitioned from software development into research, and is interested in how software development practices can be used in research. Institutionally, we have a commitment to accelerate taxonomy using digital practices, and we started a collaborative project to explore this, using institutional knowledge from the e-taxonomic approaches, but exploring what technical advances could be used in e-taxonomy today. 
    video_offset: 0m31s
  - img: /assets/images/tdwg2022-ltd14/Slide3.PNG
    img_alt: "Explain community context"
    notes: |
      Moving up to the community in which we work - one of our aims in biodiversity informatics is to build a digital extended specimen, integrating specimens and their derived data across multiple infrastructures, allowing the investigate of wider research questions. A healthy community will support a range of different approaches as we determine how to reach this aim. We can envisage these appraoches as a spectrum from large scale computation approaches that operate on large volumes of aggregated data (like the [GBIF clustering work](https://www.gbif.org/news/4U1dz8LygQvqIywiRIRpAU/new-data-clustering-feature-aims-to-improve-data-quality-and-reveal-cross-dataset-connections)), to a distributed set of lightweight tools that allow users to conduct link construction in context, closer to their day to day work.
    video_offset: 1m33s
  - img: /assets/images/tdwg2022-ltd14/Slide4.PNG
    img_alt: "Explain community context - where we're focussing"
    notes: |
      We're focussing on tools for researchers in this project, though we aim that data generated here will feed into more automated approaches - both by providing expert generated links that can be used as training data, and by allowing experts to verify the outputs of machine learning processes. 
      We also want to try to help make discussions about the digital extended specimen a little more concrete, by having actual examples and workflows that can be used as the basis for discussions and planning.
    video_offset: 2m40s
  - img: /assets/images/tdwg2022-ltd14/Slide5.PNG
    img_alt: "Based on existing software (Obsidian) - its attributes"
    notes: |
      We're basing this work on an existing piece of software - [Obsidian](https://obsidian.md).
      We said that we're trying to bring across useful working practices from software development to research management - *reuse* is a core principle in software development and here we're trying to build on an existing toolset and supportive community to allow us to make faster progress.
      We have a biodiversity crisis: faster progress - and wider participation - is vital.
    video_offset: 2m54s
  - img: /assets/images/tdwg2022-ltd14/Slide6.PNG
    img_alt: "Attributes should be familiar  - shared with Open Refine"
    notes: |
      These attributes should be familiar as they are shared with a tool which we have adopted with some success in our community: [Open Refine](https://openrefine.org/). We've seen that the use of a generic tool, with focussed technical contributions and teaching resources has allowed us to democratize data cleaning. We'd like to investigate if we can build on Obsidian and democratize data linkage.
    video_offset: 5m53s
  - img: /assets/images/tdwg2022-ltd14/Slide7.PNG
    img_alt: "Extend Obsidian for specimen research"
    notes: |
      What we've done - extended Obsidian for specimen research, by developing a set of plugins that allow a researcher to access data: specimens from [GBIF](https://www.gbif.org), names from the [International Plant Names Index](https://www.ipni.org), collections from the [Global Registry of Scientific Collections](https://www.gbif.org/grscicoll), people from [Bionomia](https://bionomia.net) and literature from [crossref](https://crossref.org). The demo software includes a worked example showing the creation of links, and spatial and network exploration of linked data. The demo also shows how key entities (specimens) can be cited in new work, promoting open science working practices.  
    video_offset: 7m10s
  - img: /assets/images/tdwg2022-ltd14/Slide8.PNG
    img_alt: "Demo screenshot"
    notes: "The demo includes an overview of how we can work with text data, highlighting a scientific name and searching for it in IPNI, retrieving name publication data including type citation data, search for type specimens in GBIF, search for collector profiles in Bionomia, using the DOI attached to the IPNI record to get bibliographic information back from crossref. The demo shows how the Obsidian user interface enables a user to link up data and to explore data visually, using a network of links"
    video_offset: 8m11s
  - img: /assets/images/tdwg2022-ltd14/Slide9.PNG
    img_alt: "Roadmap"
    notes: |
      We've proposed a 4 phase outline roadmap - work demonstrated so far fits into phase 1 - a personal research environment. We think that we can support more advanced use cases in phases 2-4, such as the production of research websites using static site generators (here we see conceptual similarity with the GBIF hosted portal programme), production of documents with embedded specimen references, and production of datasets for harvesting by data aggregators.
      We're participating in [Open Life Sciences](https://openlifesci.org) and we will revise our roadmap as we build a community around this project.
    video_offset: 12m10s
  - img: /assets/images/tdwg2022-ltd14/Slide10.PNG
    img_alt: "Links"
    notes: |
      Some links to more information and contact details.  

      - Echinopscis:
        - Project site (background, installation instructions, roadmap, ideas for contributions): [https://echinopscis.github.io](https://echinopscis.github.io)
        - Code repositories and documentation: [https://github.com/echinopscis](https://github.com/echinopscis)
      - Obsidian:
        - [https://obsidian.md](https://obsidian.md)
      
      You can find me on github, my handle is [@nickynicolson](https://github.com/nickynicolson). Since I wrote these slides I've moved from twitter (where some old stuff is still available at [@nickynicolson](https://twitter.com/nickynicolson)) to Mastodon where I am [@nickynicolson@mastodon.social](https://mastodon.social/@nickynicolson)
    video_offset: 14m41s
vimeo_link_embed: https://player.vimeo.com/video/762130677?h=997405b126
vimeo_link_simple: https://vimeo.com/762130677
---

Video and annotated slide deck for lightning talk "Open science tools: Supporting hands-on creation of the \"digital extended specimen\"" from the Biodiversity Information Standards 2022 conference in Sofia, Bulgaria. Abstract: [doi:10.3897/biss.6.91123](https://doi.org/10.3897/biss.6.91123)
