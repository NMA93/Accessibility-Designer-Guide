---
layout: documentation
nav_exclude: true
---

# Documentation
{: .no_toc .fs-11 }

This documentation serves as an additional text for the submission of the Accessibility Designer Guide as the final thesis of the course of studies HF IAD 2017.
{: .fs-6 .fw-300 }

[Back to the guide](/docs){: .btn .btn-purple }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Choice of topic
As a UX designer I am daily confronted with the challenge of combining usability and accessibility. Finding the right balance is a big challenge. This topic is more than just a thesis for me. It is a way of working that I try to internalize, and I am only at the beginning. In the year 2020, I believe it is not acceptable for user groups to be excluded from digital solutions. That's why I wanted to focus more on the topic of accessibility.

A major problem is the current accessibility guides, they are not designed in an appealing way. They are often difficult to understand or too much addressed to developers. Designers look for the information on medium or other blogs. I wanted to create a place that collects this knowledge in an interactive and appealing way.

----

## Benchmark analysis
Current guides dealing with this topic are very detailed. However, they are quite complicated for designers to read and understand. Many of the guides are out of date. It is therefore understandable that blogs fill this gap and serve as a source for designers.

<img src="{{ '/assets/images/documentation/w3c.png' | prepend: site.baseurl }}" alt="The WCAG guidelines are the bible of accessibility and cover all topics in detail. However, I have always felt overwhelmed because the site is not very well designed. Also, the topics for developers and designers are not always separated."/>
The WCAG guidelines are the bible of accessibility and cover all topics in detail. However, I have always felt overwhelmed because the site is not very well designed. Also, the topics for developers and designers are not always separated. [WCAG – Guidelines](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0&currentsidebar=%23col_overview#top"){:target="_blank"}
{: .fs-3 .mb-6 }

---

## Design decision
The current design of the guide is based on a benchmark analysis for guides used for reference. Page navigation is essential, the user must know where he is and which chapters are available. Therefore only a page navigation that offers a permanent overview is suitable.

<img src="{{ '/assets/images/documentation/material.png' | prepend: site.baseurl }}" alt="Material Design is similar in structure to this guide. The navigation is permanently visible and the user is supported by a table of contents."/>
Material Design is similar in structure to this guide. The navigation is permanently visible and the user is supported by a table of contents. [Google – Material Designs](https://material.io/design/usability/accessibility.html#understanding-accessibility"){:target="_blank"}
{: .fs-3 .mb-6 }

<img src="{{ '/assets/images/documentation/apple_dev.png' | prepend: site.baseurl }}" alt="With Apple it is exactly the same, a permanent navigation with an indication of where the reader is located is necessary."/>
With Apple it is exactly the same, a permanent navigation with an indication of where the reader is located is necessary. [Apple – Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines/macos/overview/themes/"){:target="_blank"}
{: .fs-3 .mb-6 }

### Purple/Orange
These colours were chosen because they represent a recommended colour combination for barrier-free design.

<img src="{{ '/assets/images/documentation/colour_doc.png' | prepend: site.baseurl }}" alt="Both colours meet at least the AA standard"/>
Both colours meet at least the AA standard.
{: .fs-3 .mb-6 }

### Font
The Inter as basis font is characterized by a very good readability. This font was especially designed for displays and works perfectly even in the smallest applications.

ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz1234567890 ?!()[]{}&*^%$#@~ 
{: .code-example .mb-6 .fs-10 .fw-900  }

---

## Structure
The guide starts by explaining accessibility as the overall topic. To better place this topic in the context of the design, this overall topic also takes up the 10 heuristics. Thus it is shown that usability and accessibility go hand in hand. All the later chapters are labelled with heuristics, making accessibility through usability understandable for designers.

<img src="{{ '/assets/images/documentation/labels.png' | prepend: site.baseurl }}" alt="Each chapter is linked to the corresponding heuristics."/>
Each chapter is linked to the corresponding heuristics.
{: .fs-3 .mb-6 }

---

## Techology
Since this guide is very text-heavy and should allow easy editing of the content, I decided to use jekyll. This technology enabled me to capture large amounts of text in markup and compile it directly into an html page.

### Just the docs
Just the docs was used as basis, because it is one of the most developed jekyll themes. It fits almost all the requirements I had for my guide.

<img src="{{ '/assets/images/documentation/docs.gif' | prepend: site.baseurl }}" alt="Just the docs met all the criteria I needed for this task "/>
Just the docs met all the criteria I needed for this task [Just the docs – github](https://github.com/pmarsceill/just-the-docs"){:target="_blank"}
{: .fs-3 .mb-6 }

- The code is semantically correct
- The navigation shows the current location
- Breadcrumbs
- Search
- Simple creation of a menu structure
- Cooperation in the future is possible

---

## Next steps
Several steps are planned in the near future. It is very important that this guide is not seen as completed. The current status should only be the starting point. 

### Reviewing content
The content must be thoroughly reviewed again, currently the site is in a working state which is ready for submission. For a publication the guide is not developed enough.

### Patterns
Patterns will be included in the guide, this will be an important part of the guide in the future. Actually this is one of the most important parts for designers, but it didn't make sense for me to publish it if the foundation is not developed enough.

### Publication and collaboration
Since I can't do this all by myself, this guide will be completely designed for collaboration in the future. Everybody can be a part of it and this collection of knowledge will continue to grow.

---

[Back to the guide](/docs){: .btn .btn-purple }
