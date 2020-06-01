---
layout: default
title: Keyboard friendly
parent: Architecture
nav_order: 5
---

# Keyboard friendly
{: .no_toc }
{: .fs-9 }

We usually use the mouse or trackpad to navigate around a website. But not all users can use a website in the way we as designers often imagine.
{: .fs-6 .fw-300 }

Consistency and standards
{: .label .label-black }
Flexibility and efficiency of use
{: .label .label-black }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Why it is important

 Users with disabilities often use the keyboard to navigate on a page. In general, a website should be operable with the keyboard without any restrictions. In most cases it is the task of developers or designers with code knowledge to ensure this. However, even in the design phase, some considerations can be made without code to improve keyboard accessibility and help the developers to optimize the content for keyboard use. 

## Focus indicators

The focus indicator of a website is a useful tool to improve the usability of the website by using the keyboard. But let's be honest, the default focus indicators in the browser are not that great. **One of the most common problems, they don't fit into the design**. Instead of removing the indicators now, they should be actively designed and planned from the beginning. Because **there are possibilities to design them, which unfortunately are often forgotten by designers**.

![](//placehold.it/800x400)
Default focus indicator in Chrome.
{: .fs-2 .fw-800 .mb-6 }

When it comes to designing focus indicators, the following should be considered:

- The size and shape of the indicator should **stand out from the current element**.
- The indicator should have **enough contrast**.
- The colour of the indicator should **fit into the design**, but stand out clearly enough.
- Make sure that the indicator looks the **same on all browsers**.
- Be sure that the indicator can be **applied to all elements**.
{: .mb-8 }

### Here are some examples of nicely implemented custom focus indicators:
{: .no_toc }

![](//placehold.it/800x400)
On the [myswitzerland](https://www.myswitzerland.com/ "Website: myswitzerland.com") website, the focus is elegantly integrated into the design. An outline and a drop shadow serve as indicators here. This creates the impression that the focus surrounds an invisible button.
{: .fs-2 .fw-800 .mb-6 }

![](//placehold.it/800x400)
On the [sbb](https://www.ssb.ch/ "Website: sbb.ch") website, the focus was less elegantly integrated, but great attention was given to usability and contrast.
{: .fs-2 .fw-800 .mb-6 }

---

## Structure of the Page

As we have discussed in the chapter on <a href="/Accessibility-Designer-Guide/02-Architecture/03-Titles%20and%20semantic/">Titles and semantic</a>, the semantic of a website, means structuring the elements on a site into clear groups based on their meaning. This can greatly improve the ease of use of the keyboard.

![](//placehold.it/800x400)
Structuring the Website into clear sections.
{: .fs-2 .fw-800 .mb-6 }

This allows the focus indicator to jump from element to element more quickly and easily. As a designer, it makes sense to design in **individual elements from the very beginning, so that clear groups of elements are later developed on the page**.

---

## Skip buttons and hidden keyboard features
A very important feature when operating websites through the keyboard are hidden keyboard features. These are navigation points which can only be reached by using the keyboard, for example we can have a closer look at the google search. After a search, we can enter the separate keyboard menu by using the tab key. This way keyboard users can skip links in the header and immediately go to the main content, this is a so-called skip button. This means that we have to plan additional space in the navigation to fit a keyboard navigation.

---

## Do not use too many link sections

People with visual or physical disabilities navigate through a website using a screen reader or keyboard, and if teasers and links are repeatedly inserted into relevant content, the user experience can be severely impaired. This is because users with screenreaders or keyboard navigation can later ignore irrelevant content as users can without impairment. It is better to insert such sections at the bottom of a page so that users with screen readers can also ignore them.

Translated with www.DeepL.com/Translator (free version)

<img src="{{ '/assets/images/architecture/medium_architecture.png' | prepend: site.baseurl }}" alt="In this picture we see a  page on which articles are read. As a user of a screen reader, I do not want to be taken out of context by the article because related articles are suggested to me. Therefore, it makes sense for all users to place them at the end of the article, like in this picture."/>
A good example of this are pages on which articles are read. As a user of a screen reader, I do not want to be taken out of context by the article because related articles are suggested to me. Therefore, it makes sense for all users to place them at the end of the article. [medium](https://medium.com/ "medium"){:target="_blank"}
{: .fs-3 .mb-6 }

---

##### Links
{: .no_toc }

[W3C – Keyboard Accessible](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0#keyboard-accessible "W3C – Keyboard Accessible") <br>
[W3C – Focus Visible](https://www.w3.org/WAI/WCAG21/Understanding/focus-visible "W3C – Focus Visible"){:target="_blank"} <br>
[W3C – Bypass Blocks](https://www.w3.org/WAI/WCAG21/Understanding/bypass-blocks "W3C – Bypass Blocks"){:target="_blank"} <br>
