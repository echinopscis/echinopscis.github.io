---
title: Ebbe Neilsen Challenge 2022
date: 2022-08-12 12:00
categories: [News]
---

This project has been submitted as an entry in the [GBIF][gbif] [Ebbe Neilsen Challenge 2022][enc].

**Team** Nicky Nicolson<sup>1</sup>, Isabel Larridon<sup>2</sup>, Eve Lucas<sup>2</sup> 
(1) RBG Kew, Digital revolution, (2) RBG Kew, Accelerated taxonomy

**Abstract**
> As a biodiversity informatics community, we've mobilised and interconnected a wide array of information, including specimen collections, published literature and metadata resources which compile facts about collections and the people that work with them. We’ve defined data standards to facilitate data interoperability and tools development. Along with colleagues in allied research disciplines, we’ve helped develop training resources, enabling researchers to automate routine tasks like data access and reference management. We've also started to explore how we could realise the vision of the digital extended specimen, which would integrate specimens and associated data across multiple research infrastructures, allowing the investigation of wider scale research questions. How this would be achieved is still the subject of discussion and experimentation: an open community will support a diverse range of approaches.  
>
> In the construction of the digital extended specimen - linking together specimens and their uses - we can envision useful activities operating at very different scales: from large scale computational processes run at (or between) research infrastructures, to an ecosystem of lightweight tools that support link construction in context, closer to researchers. A flexible editing environment enabling in-context link construction could make a contribution similar to that of [Open Refine](https://openrefine.org/), which has been effective at democratizing data manipulation and cleaning. We also recognise that expert created links could supply valuable training data for the development of machine learning approaches, which will be needed to achieve data linkage at scale.  
>
> This submission is a prototype desktop research environment based on the notetaking tool [Obsidian](https://obsidian.md), with the aim of opening a discussion about how a link-aware editor for semi-structured data plus standard open science tools and practices (i.e. those covered by training resources such as [software](https://software-carpentry.org/), [data](https://datacarpentry.org/) and [author](https://authorcarpentry.github.io/) carpentry) could be used as a flexible research environment. Our aim is to enable researchers to start to develop the digital extended specimen at research time, but without being prescriptive about their workflow.
> 
> Obsidian is a "personal knowledge manager" that emphasises linking. Its data is stored locally (so it is accessible offline), using open file formats (markdown text files with optional front-matter - also stored in text, in YAML format). Markdown is a lightweight markup language for creating formatted text. "YAML" ("Yet Another Markup Language") is a human-readable data serialization format based on key/value pairs. These open, accessible data storage formats offer researchers confidence that their valuable data will always be accessible offline and in the long term, without reliance on an external software service or complex data access processes. It is possible that concerns about long-term access to valuable research data may have inhibited wholescale moves towards existing online e-taxonomic systems. Obsidian has an active user and developer community, and its plugin model allows flexible configuration to support a variety of different uses - one common usage profile is to enable research writing, with plugins to cite bibliographic works and translate citation placeholders on document production. This challenge submission expands this model to enable a taxonomic researcher to easily access and cite other relevant data entities - specimens mobilised through GBIF, names from the International Plant Names Index, collections from the Global Registry of Scientific Collections, people from Bionomia - and explore a network of links.
> 
> We are interested in examining how software development working practices (storage of data and text in open formats, pipeline processing, revision control, dependency management and continuous integration) can be applied to research management and facilitate open science. We aim to develop this work in the following phases, supporting a range of different groups in the biodiversity informatics community:
> 
> 1. Personal research environment based on Markdown authoring and linking (the focus of this submission)
	- Supports *researchers* (tools providing access to relevant data), *data managers* (mobilisation of data into research environments; more effective citation of data)
> 1. Web publication using static site generators: Obsidian generated markdown can be processed to generate a static website. We see conceptual similarities with the [GBIF hosted portal](https://www.gbif.org/hosted-portals) work here.
	- Supports *researchers* (route to share data more easily and invite collaboration); *educators* and *next generation researchers* (opening the research process to explain the stages of taxonomic work).
> 1. Document production: pipelines to process markdown and structured bibliographic/specimen references to document formats like Word, PDF and HTML
	- Supports *researchers* (automation of routine tasks), *data managers* (more effective citation of data); *publishers* (streamlined comment and review process).
> 1. Dataset production: tools to process markdown and YAML frontmatter to DarwinCore
	- Supports: *researchers* (micro-publishing of datasets), *data managers* (enhanced data linkage) *data publishers* (more complete data environment).
>
> The main principle has been to recognise that research is a creative process, and that researchers must be "open to choose" how they organise their work. With this in mind, though we aim to support "usage profiles" which can help create, collaborate and publish research works and datasets, the technical contributions underpinning these will form a small toolkit which can be delivered incrementally and re-assembled in different ways to support a variety of different working patterns. We don't want to propose any solutions with complex signup requirements or a steep learning curve; we want to ensure that any skills necessary to work with this toolkit will be transferable to other open science tools and practices.
> 
> As workers active in botany and informatics, we consider the development of this toolkit as fundamental to e-taxonomic undertakings to build an online reference system in which all known plant species are described, as well as to significant acceleration of parts of the taxonomic process to address the biodiversity crisis.
>
> Our aim is to experiment, hear different views and to understand researchers and technologists needs. We anticipate these including areas such as community development, technical software development, and construction of exemplar datasets and training resources. We've been selected to participate in the sixth [Open Life Sciences (OLS)](https://openlifesci.org/) cohort, which helps projects apply open principles in their work, with an emphasis on community building and inclusivity. We look forward to using these techniques to explore this topic with our current (and future) colleagues.


[gbif]: https://gbif.org
[enc]:  https://www.gbif.org/news/77jGLQMqzZtjQi10AxAgrY/2022-ebbe-nielsen-challenge-seeks-open-data-innovations-for-biodiversity
[enc-appl]: https://github.com/echinopscis/ebbe-neilsen-application
