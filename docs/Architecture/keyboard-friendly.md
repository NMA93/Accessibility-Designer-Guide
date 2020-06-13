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

<img src="{{ '/assets/images/hero/keyboard.png' | prepend: site.baseurl }}" alt="Title Picture keyboard friendly" title="Title keyboard friendly"/>
{: .mt-6 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Why it is important

Users with disabilities often use the keyboard to navigate a page. In general, a Web site should be fully accessible using the keyboard. In most cases, it is the job of developers or designers with code knowledge to ensure this. However, some considerations can be made in the design phase without code to improve keyboard accessibility and help developers optimize content for keyboard use.
{: .mb-6 }

#### For the following people, a Web site that is not accessible using the keyboard can be a problem:
{: .no_toc .mb-5 }

- People who are blind and navigate with a screen reader
- Users who are dependent on keyboard navigation
- People with temporary impairments, for example injured hands
- Old people who navigate using the keyboard

---

## Structure of the Page

As we have discussed in the chapter [semantics]({{ site.baseurl }}{% link docs/Architecture/semantics.md %} "semantics"), the semantic of a website, means structuring the elements on a site into clear groups based on their meaning. This can greatly improve the ease of use of the keyboard.
{: .mb-6 }

<img src="{{ '/assets/images/semantics/semantic_structure.png' | prepend: site.baseurl }}" alt="In this picture you can see a page that has been broken down into its semantic structure."/>
In this example clear structures can be seen on the page. If modules are designed within this structure, implementation in the code is easier later.
{: .fs-3 .mb-6 }

A clear separation of the page into its semantic components makes it easier for the user to navigate with the keyboard. The user can jump from section to section and from element to element. As a designer, it makes sense to design in individual semantic elements from the very beginning, so that clear groups of elements are later developed on the page.

---

## Focus indicators

The focus indicator of a website is a useful tool to improve the usability of the website using the keyboard. But let's be honest, the default focus indicators in the browser are not that great. One of the most common problems is that they do not fit into the design. Instead of removing the indicators now, they should be actively designed and planned from the beginning. After all, there are ways of designing them that are unfortunately often forgotten by designers.

<img src="{{ '/assets/images/keyboard/focus_default.png' | prepend: site.baseurl }}" alt="In this picture we see the default focus indicator in Chrome."/>
Default focus indicator in Chrome.
{: .fs-3 .mb-6 }

#### When it comes to designing focus indicators, the following should be considered:
{: .no_toc .mb-5 }

- The size and shape of the indicator should stand out from the current element
- The focus indicator should stand out from the hover and active status of the items
- The indicator should have enough contrast
- The colour of the indicator should fit into the design, but stand out clearly enough.
- Make sure that the indicator looks the same on all browsers
- Be sure that the indicator can be applied to all elements
{: .mb-6 }


<img src="{{ '/assets/images/keyboard/focus_my_switzerland.png' | prepend: site.baseurl }}" alt="In this picture we see a focus indicator, wich is elegantly integrated into the design. An outline and a drop shadow serve as indicators here. This creates the impression that the focus surrounds an invisible button."/>
On the [myswitzerland](https://www.myswitzerland.com/ "Website: myswitzerland.com"){:target="_blank"} website, the focus is elegantly integrated into the design. An outline and a drop shadow serve as indicators here. This creates the impression that the focus surrounds an invisible button.
{: .fs-3 .mb-6 }

---

## Skip buttons and hidden keyboard features
A very important feature when operating websites through the keyboard are hidden keyboard features. These are navigation points which can only be reached by using the keyboard, for example we can have a closer look at the google search. After a search, we can enter the separate keyboard menu by using the tab key. This way keyboard users can skip links in the header and immediately go to the main content, this is a so-called skip button.
{: .mb-6 }

<video width="100%" height="auto" controls>
    <source src="{{ '/assets/videos/skip.mp4' | prepend: site.baseurl }}">
</video>

In this example of [Google search](https://google.com/ "Google search"){:target="_blank"} we see a button to skip after the result appears when we use keyboard navigation.
{: .fs-3 .mb-6 }


#### Good to know
{: .no_toc }
This means that we have to plan additional space in the navigation to fit a keyboard navigation.
{: .code-example }

---

## Do not use too many link sections

People with visual or physical disabilities navigate through a website using a screen reader or keyboard, and if teasers and links are repeatedly inserted into relevant content, the user experience can be severely impaired. This is because users with screenreaders or keyboard navigation can later ignore irrelevant content as users can without impairment. It is better to insert such sections at the bottom of a page so that users with screen readers can also ignore them.

<img src="{{ '/assets/images/architecture/medium_architecture.png' | prepend: site.baseurl }}" alt="In this picture we see a  page on which articles are read. As a user of a screen reader, I do not want to be taken out of context by the article because related articles are suggested to me. Therefore, it makes sense for all users to place them at the end of the article, like in this picture."/>
A good example of this are pages on which articles are read. As a user of a screen reader, I do not want to be taken out of context by the article because related articles are suggested to me. Therefore, it makes sense for all users to place them at the end of the article. [medium](https://medium.com/ "medium"){:target="_blank"}
{: .fs-3 .mb-6 }

---

##### Links
{: .no_toc }

[W3C – Keyboard Accessible](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0#keyboard-accessible "W3C – Keyboard Accessible") <br>
[W3C – Focus Visible](https://www.w3.org/WAI/WCAG21/Understanding/focus-visible "W3C – Focus Visible"){:target="_blank"} <br>
[W3C – Bypass Blocks](https://www.w3.org/WAI/WCAG21/Understanding/bypass-blocks "W3C – Bypass Blocks"){:target="_blank"} <br>
