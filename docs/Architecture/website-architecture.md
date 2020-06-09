---
layout: default
title: Website architecture
parent: Architecture
nav_order: 1
---


# Website architecture
{: .no_toc }
{: .fs-9 }

Simple, short and logical paths within the website increase the usability not only for people with disabilities but for all users. But what do you need to consider when creating a website architecture?
{: .fs-6 .fw-300 }

Consistency and standards
{: .label .label-black }

<img src="{{ '/assets/images/architecture.png' | prepend: site.baseurl }}" alt="Title Picture architecture." title="Title Picture architecture."/>
{: .mt-6 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What problems can be caused by the website architecture?
Digital systems should guide the user to his destination as quickly and easily as possible. This requires a well thought-out and consistent website architecture. People with disabilities must be able to rely on the sites meeting certain standards.
{: .mb-6 }

#### An inconsistent and not well thought out architecture can be a problem for the following users:
{: .no_toc .mb-5 }

- People with a visual impairment
- People who are blind and navigate with a screen reader
- People who navigate through the site with the keyboard

In order to make it as easy as possible for these user groups to navigate within the site, it makes sense to observe the following rules when structuring the pages.

---

## Hierarchy
The hierarchy of a website determines how we consume the content of a page. For people who rely on screen readers or use the keyboard to navigate through a website, it is important that the hierarchy follows a logical sequence.

<img src="{{ '/assets/images/architecture/flow.png' | prepend: site.baseurl }}" alt="In this example we see a clear hierarchical structure of the pages which is divided by 4 category landing pages."/>
In this example we see a clear hierarchical structure of the pages which is also structured by 4 category landing pages (on level 2).
{: .fs-3 .mb-6 }

A common mistake that is made is the inconsistent use of categories defined in a site architecture. In our example we see 4 main categories on level 2, each new content must be under one of these categories. Standalone pages make the site confusing for all users.

<img src="{{ '/assets/images/architecture/categories.png' | prepend: site.baseurl }}" alt="In this example we see a clear hierarchical structure of the pages which is divided by 4 category landing pages."/>
If main categories have been defined, it is required to comply with them.
{: .fs-3 .mb-6 }


---
 
## Category landing pages - multiple ways

A content-relevant page should be accessible via several ways within a page architecture. For example, in addition to navigation, a page can also be accessible via a teaser. Ideally, there should be several content hubs or category landing pages within a page architecture, which only serve to guide the user to his or her destination. These content hubs or category landing pages can be seen as an extension of the navigation and therefore do not disturb users of screen readers. This can help people with cognitive and visual impairments to find content faster.

<img src="{{ '/assets/images/architecture/multiple_ways.png' | prepend: site.baseurl }}" alt="In this picture we see an example of a page which can be reached via multiple ways (navigation) or (content hub/category landing pages)."/>
In this example we can reach the target page (on level 3) either via the navigation (on any level 1, 2 or 3) or the content hub/category landing pages (on level 2).
{: .fs-3 .mb-6 }

#### Good to know
{: .no_toc }
Pages that only serve to redirect the user to other pages should not contain relevant content. Since they do not have to be visited to navigate the site. Additionally, link-heavy sections in a content-relevant page disturb the user experience with screen readers.
{: .code-example }

---

##### Links
{: .no_toc }

[W3C - Multiple Ways](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0#multiple-ways "W3C - Multiple ways"){:target="_blank"} <br>
[Nielsen Norman Group – Top 10 Information Architecture (IA) Mistakes](https://www.nngroup.com/articles/top-10-ia-mistakes/ "Nielsen Norman Group – Top 10 Information Architecture (IA) Mistakes"){:target="_blank"} <br>

