---
title: Wikidata obsidian plugin
date: 2023-12-01
categories: [Talks]
twitter_description: 'Presented an Obsidian Wikidata plugin at the Wikidata data modelling event 2023'
---

Both at TDWG and at the recent TaxonWorks event, we discussed the "entity explosion" browser plugin (that loads the relevant Wikidata item based on your current context) and thought that it would be useful to have a similar plugin available for Obsidian, and a few short weeks later... here it is (an alpha version).
A post about this plugin was picked up by the Wikidata community and resulted in a invitation to present it in a lightning talk at the [Wikidata Data Modelling](https://www.wikidata.org/wiki/Wikidata:Events/Data_Modelling_Days_2023) event (30th November - 2nd December 2023). 

## What is Wikidata

Wikidata ([www.wikidata.org](https://wikidata.org)) is a structured data resource that underlies Wikipedia. Its used in Biodiversity Informatics in [Bionomia](https://bionomia.net) (to store biographical profiles for historical collectors / determiners), and is being used in the development of a data standard for the modelling of research expeditions. 
Many identifiers for entities that we recognise in biodiversity informatics are stored in Wikidata. The information can be accessed using SPARQL queries, the [Wikidata query service](https://query.wikidata.org/) is a good place to start to explore these. SPARQL queries can also be run over a web API, and you can get the results back in structured format for integration into tools and processes.

## What is Entity Explosion

[Entity Explosion](https://github.com/99of9/Entity-Explosion) is a web browser plugin that loads the relevant Wikidata item based on your current context. It works by examing the URL of the page that you currently have loaded. If the URL pattern matches the URL format specified in a wikidata property, then the browser extracts the identifier from the URL and uses it to make a query to Wikidata, and relevant entities are shown in a panel.

A walkthrough:

I load the author profile page for Richard Brummitt in IPNI - the URL for this page is: https://www.ipni.org/a/1221-1

Entity Explosion looks at the URL and detects that this matches the URL format for the property [IPNI author ID](https://www.wikidata.org/wiki/Property:P586). It extracts the identifier part (1221-1) and uses this to build a query to wikidata - requesting the entity with P586 = 1221-1. This query matches the wikidata entity ["Richard Kenneth Brummitt"](https://www.wikidata.org/wiki/Q372403). The entity details are shown in a pop-up panel.

![Screenshot of entity explosion browser plugin operating on an author profile page from the International Plant Names Index](/assets/images/taxonworks-together-2023/entity-explosion-example.jpg)

## Building a wikidata plugin in Obsidian

In Obsidian, we wouldn't have a "current URL" for a page the way that you would in a web browser. But - remember that Obsidian pages are formatted in Markdown with optional structured YAML frontmatter. We should be able to map frontmatter property names to wikidata property identifiers, and use these to build the query to wikidata. We'd then show the wikidata entity in a sidebar panel.

## Demo

### Screenshot showing sidebar loaded from mapped frontmatter properties

#![A page in Obsidian with frontmatter specifiying a Wikidata entity ID, and the corresponding Wikidata entity displayed in a sidebar panel](/assets/images/wikidata-dm-2023/obdisian-wikidata-q42.png)

### Screenshot showing use with Taxonomic Literature II (TL2)

Anton Savchenko ([sav-che on github](https://github.com/sav-che)) has created an Obsidian vault containing the reference work Taxonomic LIterature II. Many of the botanists who have biographical profiles in thsi work also have data in Wikidata. I tried bulk editing to move the botanists author abbreviation (the "standard form" of their name) to the page frontmatter, and updated the settings for the plugin to map "std_form" to the Wikidata property [P428 (botanist author abbreviation)](https://www.wikidata.org/wiki/Property:P428)

#![A page from TL-2 in Obsidian with a wikidata sidebar showing details of the author profiled in the page](/assets/images/wikidata-dm-2023/obdisian-wikidata-tl2.png)


## What's next

As well as showing data in the sidebar, it may be useful to be able to bring the data back into Obsidian and use it in a template to create a new page or entity reference.

Some kind of history navigation - to allow the user to move forward and back through the entities that are displayed in the sidebar - might also be useful.

This model - either querying using full text or by mapping frontmatter properties to API parameters - could also be applied to the other data access plugins available as part of echinopscis. For example - if a user is searching for a specimen that is mobilised through the GBIF network, currently the only way to see the details for that specimen is to create a local page in Obsidian. It may be better to first inspect the specimen in a sidebar, then choose to create a local representation when you are sure that this is the specimen that you want.  

## Try it out

You can install the plugin from the [obsidian wikidata plugin github repo](https://github.com/echinopscis/obsidian-wikidata-plugin). Feedback in the form of issues / bug reports etc welcome on the [issue tracker](https://github.com/echinopscis/obsidian-wikidata-plugin/issues) or here in the comment section below. 

## Thanks

[Entity Explosion](https://github.com/99of9/Entity-Explosion) was the primary inspiration for this work - thanks to [Toby Hodges](https://github.com/99of9) for developing it. I also made extensive use of the [Obsidian book search plugin](https://github.com/anpigon/obsidian-book-search-plugin/) as a model for the plugin development and project setup - thanks to [anpigon](https://github.com/anpigon).

