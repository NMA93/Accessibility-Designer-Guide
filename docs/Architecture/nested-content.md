---
layout: default
title: Nested content
parent: Architecture
nav_order: 7
---

# Nested content
{: .no_toc }
{: .fs-9 }

Additional content is used when the user should not be confronted with the whole content immediately.  On the one hand the user is not overwhelmed, on the other hand the hiding of content can cause problems.
{: .fs-6 .fw-300 }

Consistency and standards
{: .label .label-black }
Aesthetic and minimalist design
{: .label .label-black }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---


## Why it is problematic to nest information

If content is nested by using tabs or accordions, the page appears more organized and structured. However, the complexity of the page and how to use it increases.
{: .mb-8 }

#### The following problems may occur:
{: .no_toc .mb-5 }

- Users overlook content
- If unsuitable contents are nested, the usability for all users is reduced
- The demands on cross-device design are increasing
- For all users and special users with disabilities, the site becomes more complicated to use with screen reader and keyboard

---

## How to nest content correctly
Basically nested information are not bad, correctly implemented they can improve the usability of a page. An important part is the implementation of the elements in the code. For example, the semantically correct implication: see chapter [Semantics](/Accessibility-Designer-Guide/docs/Architecture/semantics/). But also in the design there are certain rules that have to be observed.

### Announce the content to be expected
If content is nested, it is important to provide it with a label that describes the content. This way the user knows exactly what to expect. See also chapter [Context](/Accessibility-Designer-Guide/docs/Architecture/context/) for more informations about meaningful labels. The following example with an accordion shows this:

![](//placehold.it/800x400)
Due to the unclear labeling of the individual tabs the user has no chance to figure out what to expect. This is not only a usability problem for people with disabilities. 
{: .fs-2 .fw-800 .mb-6 }

![](//placehold.it/800x400)
After the tabs are clearly labeled, it is clear to the user what to expect behind the functions.
{: .fs-2 .fw-800 .mb-6 }

### Do not nest important functions
If content is nested, it should not be an essential part of the operation of the site. The operability of the site must not suffer. Otherwise it can be confusing for the users, because they cannot find important functions.

![](//placehold.it/800x400)
Since the CTA button is located inside the accordion, it is easily overlooked. Furthermore, for users with Screen Reader, an important function is unnecessarily nested.
{: .fs-2 .fw-800 .mb-6 }

![](//placehold.it/800x400)
Important elements should be placed on a higher level outside the nested elements.
{: .fs-2 .fw-800 .mb-6 }

### Display what is active
If information is nested, it is important to show the user which elements are currently active. Often a colourful highlighting is sufficient, optimnally this is supported by backgrounds. This allows the user to set the content in context more easily. See also chapter [Context](/Accessibility-Designer-Guide/docs/Architecture/context/). 
{: .mb-8 }

#### the following example shows the problem
{: .no_toc .mb-5 }

![](//placehold.it/800x400)
We see here a highlighting of the active tab, but it is not clear enough for all users. People with disabilities or inexperienced internet users will not recognize this element as a tab.
{: .fs-2 .fw-800 .mb-6 }

![](//placehold.it/800x400)
Through a clear subdivision of the background, the user can see more quickly what kind of pattern this is. The element is immediately recognized as tab.
{: .fs-2 .fw-800 .mb-6 }

---

##### Links
{: .no_toc }

[W3C – Accordion](https://www.w3.org/TR/wai-aria-practices/examples/accordion/accordion.html "W3C – Accordion"){:target="_blank"} <br>
[W3C – Example Disclosure (Show/Hide)](https://www.w3.org/TR/wai-aria-practices/examples/disclosure/disclosure-faq.html "W3C – Example Disclosure (Show/Hide)"){:target="_blank"} <br>

