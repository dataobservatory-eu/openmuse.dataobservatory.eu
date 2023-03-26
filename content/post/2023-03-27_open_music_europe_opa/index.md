---
title: "Commitment to the Open Policy Analysis Guidelines"
subtitle: ""

# Summary for listings and search engines
summary: ""

authors: ["admin"]
 
# Link this post with a project
projects: ""

# Date published
date: "2023-03-27T12:00:00+01:00"
lastmod: "2023-03-27T18:19:00+01:00"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

links:
- icon: database
  icon_pack: fas
  name: Digital Music Observatory
  url: https://music.dataobservatory.eu/
- icon: play
  icon_pack: fas
  name: Smart Policy Documents
  url: https://music.dataobservatory.eu/apps/smart-policy-documents/
- icon: linkedin
  icon_pack: fab
  name: Follow us
  url: https://www.linkedin.com/company/79286750/
- icon: fa-eu-emblem
  icon_pack: far
  name: 🇪🇺 Consortium on CORDIS
  url: https://cordis.europa.eu/project/id/101095295

# Featured image
image:
  caption: ''
  focal_point: "center"
  placement: 2
  preview_only: true
  
tags:
  - Open Music Europe
  - Open Policy Analysis Guidelines
  - FAIR
---


The `Open Music Europe` consortium is committed to implementing the highest standard Open Policy Analysis Guidelines and showing best practices to the FAIR principles using reproducible research principles.  We believe that this will increase the quality and usability of our products to our target groups: European cultural policymakers, the music industry and its trade associations, researchers of music. In this blogpost we explain how we started to work and explain the next steps.

## OPA? FAIR?

The **Open Policy Analysis**[^1] is an approach to policy analysis wherein data, code, materials, and clear accounts of methodological decisions are made freely available to facilitate collaboration, discussion, and reuse. This helps a transparent policy analysis that is always inclusive to comments, and which is easy to review.  We believe that this will lead to higher quality and more transparency in the use of resources. You can read in details how the `Open Music Europe` consortium applies the OPA Guidelines to deliver its results in the [Resources/OPA](https://openmuse.dataobservatory.eu/resources/opa/) section of our project website.

[^1]: You can download the nine requirements in a tabular form on the [www.bitss.org](http://www.bitss.org/wp-content/uploads/2019/03/OPA-Guidelines.pdf) website.

The **GO FAIR** initiative of the European Open Science Cloud (EOSC)[^2] is mandatory to apply to the Horizon Europe program.  It aims to make the data and services rendered by the Open Music Europe consortium to its target groups Findable, Accessible, Interoperable and Reusable (FAIR) for machines. Compliance with this European aim requires the application of OPA on Level 3, which ensures reproduciblity and readability for machines.

[^2]: [GO FAIR website](https://www.go-fair.org/)

## In practice

Our Consortium, following best practice, placed its assumptions (which were part of our Proposal for this project) into the open science repository of the European OpenAIRE project[^3].

[^3]: Report on the European Music Economy [GO FAIR website](https://zenodo.org/record/6464782#.ZB7GltLMLlg)

The `Open Music Europe Consortium`, EUBA, SOZA and Reprex signed a Memorandum of Understanding with the Ministry of Culture of the Slovak Republic on utilizing the Open Policy Analysis results. 

<td style="text-align: center;">{{< figure src="img/blogposts_2023/MoU_signature_20230306_02_2x1.jpg" caption="From left to right: Ľubomír Burgr, Chariman of the Board (SOZA); [Dr James Edwards](https://music.dataobservatory.eu/authors/james_edwards/) Open Music Europe program director; Ferdinand Daňo, rector of EUBA; Rado Kutaš, state secretary; Tomaš Mikš, SOZA; [Daniel Antal](https://reprex.nl/author/daniel-antal/), co-founder of Reprex. Photo: [Dominika Semaňáková](https://music.dataobservatory.eu/authors/dominika_semanakova/)." numbered="false" >}}</td>

Following the requirements of **Open Analysis**, the Coordinator of Open Music Europe pledged that our researchers in WP1-2-3-4 will apply the OPA in their analysis.

### Open Analysis {#open-analysis}

- *Provide clear accounts of all methodological procedures in a way that is easily interpreted by an informed reader*: Code is clearly documented into a dynamic document, or open notebook. No spreadsheets--see further compliance in [Open Materials](/resources/opa/#open-materials). [Synyo](/authors/synyo/) is tasked to make document templates and web content that help compliance with this principle, and [Reprex](/authors/reprex/) and [Turku](/authors/utu) assist all work package leaders with various tools to comply in content with this requirement.
- *Share raw (or analytic) data and materials in a way that the analysis is reproducible with minimal effort.*  

{{% callout note %}}
The report utilizes the indicators developed in Open Music Europe D1.1 [Economy of music in Europe: Methods and indicators](https://github.com/dataobservatory-eu/economy-music-methods-indicators). See the [Resources](/resources/) part of the website for the further repositories of the Work Packages.
{{% /callout %}}


- **Share raw (or analytic) data and materials in a way that the analysis is reproducible with minimal effort.**  Analytic and raw data are made available through a trusted repository. [D1.3 Report on the European Music Economy](https://github.com/dataobservatory-eu/european_music_economy).

### Open Materials {#open-materials}

All research and innovation team members use version control software and track changes in a shared project repository. All our deliverable are delivered in a version-controlled repository. 

{{% callout note %}}
For example, the D1.1 deliverable materials can be found in this  [repository](https://github.com/dataobservatory-eu/economy-music-methods-indicators). See the [Resources](/resources/) part of the website for the further repositories of the Work Packages. This will be used for example to monitor the implementation of the `Cultural and Creative Industries Strategy of the Slovak Republic 2030` [Stratégia kultúry a kreatívneho priemyslu Slovenskej republiky 2030](https://www.culture.gov.sk/ministerstvo/strategia-kultury-a-kreativneho-priemyslu-2030/) national policy.
{{% /callout %}}


All project components (for each deliverable output) are organized in a selfcontained folder using a Standard File Structure (SFS), and a readme file is included[^4]. 

[^4]: Links to the README.md files for D1.1 [Economy of music in Europe: Methods and indicators](https://github.com/dataobservatory-eu/economy-music-methods-indicators); D1.3 [Economy of music in Europe: Methods and indicators](https://github.com/dataobservatory-eu/economy-music-methods-indicators).


The Work Package leaders ensure that the list all inputs, and their sources, and provide links or detailed references.

{{% callout note %}}
The report utilizes the indicators developed in Open Music Europe D1.1 that you can find here: [Economy of music in Europe: Methods and indicators](https://github.com/dataobservatory-eu/economy-music-methods-indicators). The report itself can be found in this repository: [Report on the European Music Economy](https://github.com/dataobservatory-eu/european_music_economy)
{{% /callout %}}

Code must be easily readable and possible to run with just one click, and produces tabular data or results[^5]. The Turku Data Science team and Reprex will assist all our research teams in making their data outputs reproducible, particularly with the development of the [dataset](https://dataset.dataobservatory.eu/) package that will ensure that our tabular data outputs will not only be readable by spreadsheet applications but also for machines, i.e. following the standards of the Statistical Data and Metadata Exchange and the W3C Consortium definition of machine-readable output.

[^5]: For stand-alone spreadsheets, this level of compliance is not applicable, we will always deliver spreadsheets with the code that created the spreadsheet. See [Resources/OPA](/resources/opa/#open-materials) 

## Open Output

Our aim is to be open, transparent and inclusive from the planning of a policy analysis till we are finished.  Our open output techniques ensure that our analysis can be easily found in global libraries, and it is connected to similar work. Read more in our *Contributors' Manual for the Data Observatories and Open Collection* about how we make the output more [findable](https://manual.dataobservatory.eu/findable.html), [accessible](https://manual.dataobservatory.eu/accessible.html), easier to integrate with other digital assets, i.e., more [interoperable](https://manual.dataobservatory.eu/interoperability.html) and more [reusable](https://manual.dataobservatory.eu/reuse.html).

**Link**:
- [Contributors' Manual for the Data Observatories and Open Collections](https://manual.dataobservatory.eu/)
