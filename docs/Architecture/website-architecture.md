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

## Do not use too many link sections

People with visual impairments navigate through a website with a screen reader, and if teasers and links are repeatedly inserted into relevant content, the user experience can be severely impaired. This is because users with screen readers cannot simply ignore or later disregard irrelevant content. It is better to insert such sections at the bottom of a page so that users with screen readers can ignore them as well.

<img src="{{ '/assets/images/architecture/medium_architecture.png' | prepend: site.baseurl }}" alt="In this picture we see a  page on which articles are read. As a user of a screen reader, I do not want to be taken out of context by the article because related articles are suggested to me. Therefore, it makes sense for all users to place them at the end of the article, like in this picture."/>
A good example of this are pages on which articles are read. As a user of a screen reader, I do not want to be taken out of context by the article because related articles are suggested to me. Therefore, it makes sense for all users to place them at the end of the article. [medium](https://medium.com/ "medium"){:target="_blank"}
{: .fs-3 .mb-6 }

---

## Multiple ways

A content-relevant page should be accessible via several ways within a page architecture. For example, in addition to navigation, a page can also be accessible via a teaser. Ideally, there should be several content hubs within a page architecture, which only serve to guide the user to his or her destination. These content hubs can be seen as an extension of the navigation and therefore do not disturb users of screen readers. This can help people with cognitive and visual impairments to find content faster.

<img src="{{ '/assets/images/architecture/multiple_ways.png' | prepend: site.baseurl }}" alt="In this picture we see an example of a page which can be reached via multiple ways (navigation) or (contenthub/parentsite)."/>
In this example we can reach the target page (1.A) either via the navigation or the content hub/parent site (1).
{: .fs-3 .mb-6 }

#### Good to know
{: .no_toc }
Pages that only serve to redirect the user to other pages should not contain relevant content. Since they do not have to be visited to navigate the site. Additionally, link-heavy sections in a content-relevant page disturb the user experience with screen readers.
{: .code-example }


### Footer navigation
Footer navigation is suitable for making pages accessible in several ways. The footer navigation should give the user an overview of the most important menu items. Useful links such as "Contact" and "Language selection" are quickly accessible.

---

## Linear flow

### Site architecture

### Within the page


---

##### Links
{: .no_toc }

[W3C - Multiple Ways](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0#multiple-ways "W3C - Multiple ways"){:target="_blank"} <br>

