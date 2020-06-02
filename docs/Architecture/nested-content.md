---
layout: default
title: Nested content
parent: Architecture
nav_order: 8
---

# Nested content
{: .no_toc }
{: .fs-9 }

Additional content is used when the user should not be confronted with the entire content immediately. On the one hand the user is not overwhelmed, on the other hand hiding content can cause problems.
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
{: .mb-6 }

#### The following problems may occur:
{: .no_toc .mb-5 }

- Users overlook content
- If unsuitable contents are nested, the usability for all users is reduced
- The demands on cross-device design are increasing
- For all users and special users with disabilities, the site becomes more complicated to use with screen reader and keyboard navigation

---

## How to nest content correctly
In general, nested information is not bad, correctly implemented it can improve the usability of a page. An important part is the implementation of the elements in the code. For example the semantically correct implication: see chapter [Semantics](/Accessibility-Designer-Guide/docs/Architecture/semantics/). But also in the design there are certain rules that have to be observed.

### Announce the content to be expected
If content is nested, it is important to provide it with a label that describes the content. This way the user knows exactly what to expect. See also chapter [Context](/Accessibility-Designer-Guide/docs/Architecture/context/) for more informations about meaningful labels.

<img src="{{ '/assets/images/nested/tab_label.png' | prepend: site.baseurl }}" alt="In this screen you see tabs that are very clearly labeled and supported by an icon."/>
On the page of [ebookers](https://www.ebookers.com/ "Website: ebookers.com"){:target="_blank"} the labels are very clearly described and are supported by an icon. For the user it is immediately clear what to expect behind this tab.
{: .fs-3 .mb-6 }

### Do not nest important functions
If content is nested, it should not be an essential part of the operation of the site. The operability of the site must not suffer. Otherwise it can be confusing for the users, because they cannot find important functions.

<div id="container1">
 <!-- The before image is first -->
 <img src="{{ '/assets/images/nested/tab_cta_x.png' | prepend: site.baseurl }}" alt="In this example the important action call button within the tabs is overlooked."/>
 <!-- The after image is last -->
 <img src="{{ '/assets/images/nested/tab_cta.png' | prepend: site.baseurl }}" alt="In this example the offers are shown and the call to action button is clearly visible."/>
</div>
{: .mb-3 }

In this example the important buton within the tabs is overlooked. The interaction with the individual products is made more difficult by the unnecessary nesting. It is better to show the offers.
{: .fs-3 .mb-6 }

### Display what is active
If information is nested, it is important to show the user which elements are currently active. Often a colourful highlighting is sufficient, optimnally this is supported by backgrounds. This allows the user to set the content in context more easily. See also chapter [Context](/Accessibility-Designer-Guide/docs/Architecture/context/). 
{: .mb-8 }

#### the following example shows the problem
{: .no_toc .mb-5 }

<div id="container2">
 <!-- The before image is first -->
 <img src="{{ '/assets/images/nested/tab_highlighting_x.png' | prepend: site.baseurl }}" alt="In this example, the tabs are simple text links and not enough marked active."/>
 <!-- The after image is last -->
 <img src="{{ '/assets/images/nested/tab_highlighting.png' | prepend: site.baseurl }}" alt="In this example, the background helps to highlight the active tab and creates the connection to the content."/>
</div>
{: .mb-3 }

In the first example it can be difficult for some users to see the active state of the tabs. In the second example, where the background is used to connect to the content, it is clear which tab is active.
{: .fs-3 .mb-6 }

---

##### Links
{: .no_toc }

[W3C – Accordion](https://www.w3.org/TR/wai-aria-practices/examples/accordion/accordion.html "W3C – Accordion"){:target="_blank"} <br>
[W3C – Example Disclosure (Show/Hide)](https://www.w3.org/TR/wai-aria-practices/examples/disclosure/disclosure-faq.html "W3C – Example Disclosure (Show/Hide)"){:target="_blank"} <br>

