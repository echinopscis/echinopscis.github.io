---
layout: home
title: echinopscis
description: An extensible notebook for open science
background: /images/Echinopsis_calochlora_2019-12-13_6735.jpg
permalink: /
---

"echinopscis" is an experiment in creating an "extensible notebook for open science" - a working environment that allows researchers to write, access data and create links between literature, specimens, names, institutions, people, traits etc.

## Key principles:

- **Control of your data**: as a researcher, you remain in control of your data. The data is stored in text format, on your local machine. Text files are an open format, they will always be accessible without any need for specialised software.
- **Open to choose your working practices**: we've provided small pieces of functionality that can be combined in many different ways, enabling researchers to be "open to choose" how to organise their work.
- **Re-usable skills**: any skills necessary to work with this toolkit should be transferable to other open science tools and practices. If you invest in time exploring this prototype software, the things you learn (markdown formatting, bibliography / citation management, document production etc) could also be applied elsewhere in your work, or in other working environments.
- **Open science**: All code and documentation (and this project site) are managed on [github](https://github.com/echinopscis) - contributions are welcome.

## Try it out:

1. [Download](https://github.com/echinopscis/echinopscis-sample-vault/releases/download/v0.0.1/echinopscis.zip) the echinopscis sample vault (zipped and pre-configured with plugins for data access and visualisation of biodiversity informatics data), and extract to a directory on your computer.
1. [Download](https://obsidian.md/download) and install Obsidian for your operating system. 
1. Launch Obsidian. You will be given three options, to: 

    - Create a new vault ("vault" is the Obsidian term for a workspace or project; the contents of a vault are "pages", arranged into "folders")
    - Open a folder as a vault
    - Open a remote vault. 

    Select the middle option: "Open folder as vault". Choose the echinopscis sample vault that you extracted in step 1. You will be asked to confirm that you trust the author of the vault, so that plugins can be enabled, click  "Trust author and enable plugins". Obsidian will show you a list of the plugins contained in the vault, you can exit this listing using the <kbd>Esc</kbd> key

1. Explore - or work through the steps listed from the "start here" page which should be listed in the navigation panel on the left of the window. (Note: If you have Obsidian installed and have opened the echinopscis sample vault, then you can open the "start here" page with [this link](obsidian://open?vault=echinopscis&file=start%20here))
1. (Optional) - install a browser bookmark that can be used to save web content (complete pages or selected text) to Obsidian - drag this link: <a href='javascript:Promise.all([import("https://unpkg.com/turndown@6.0.0?module"),import("https://unpkg.com/@tehshrike/readability@0.2.0"),]).then(async([{default:e},{default:f}])=>{function g(){var a="";if(void 0!==window.getSelection){var b=window.getSelection();if(b.rangeCount){for(var d=document.createElement("div"),c=0,e=b.rangeCount;c<e;++c)d.appendChild(b.getRangeAt(c).cloneContents());a=d.innerHTML}}else void 0!==document.selection&&"Text"==document.selection.type&&(a=document.selection.createRange().htmlText);return a}let a=g(),{title:b,byline:h,content:i}=new f(document.cloneNode(!0)).parse();function j(a){window.navigator.userAgent;var b=window.navigator.platform;return a=-1!==["Win32","Win64","Windows","WinCE"].indexOf(b)?a.replace(":","").replace(/[/\\?%*|"<>]/g,"-"):a.replace(":","").replace(/\//g,"-").replace(/\\/g,"-")}let k=j(b);if(a)var c,d=a;else var d=i;var c="";let l=new e({headingStyle:"atx",hr:"---",bulletListMarker:"-",codeBlockStyle:"fenced",emDelimiter:"*"}).turndown(d);var m=new Date;function n(a){var f=a.getFullYear().toString(),b=(a.getMonth()+1).toString(),c=a.getDate().toString(),d=b.split(""),e=c.split("");return f+"-"+(d[1]?b:"0"+d[0])+"-"+(e[1]?c:"0"+e[0])}let o=n(m),p="author:: "+h+"\nsource:: ["+b+"]("+document.URL+")\nclipped:: [["+o+"]]\npublished:: \n\n#clippings\n\n"+l;document.location.href="obsidian://new?file="+encodeURIComponent(""+k)+"&content="+encodeURIComponent(p)+c})'>Send to Obsidian</a> to your browser toolbar. ([web clipper](https://gist.github.com/kepano/90c05f162c37cf730abb8ff027987ca3) by [@kepano](https://github.com/kepano))
