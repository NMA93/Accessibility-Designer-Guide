---
layout: default
title: Context
parent: Architecture
nav_order: 7
---

# Context
{: .no_toc }
{: .fs-9 }

When we talk to a person face to face, content is often put into context. In this way misunderstandings can be avoided. The same is applicable to content on the web. If the context is not given, users cannot classify the meaning of individual elements.
{: .fs-6 .fw-300 }

Consistency and standards
{: .label .label-black }
Recognition rather than recall
{: .label .label-black }
Aesthetic and minimalist design
{: .label .label-black }

<img src="{{ '/assets/images/context/context.png' | prepend: site.baseurl }}" alt="Illustration of an exclamation mark." title="Illustration of an exclamation mark."/>
{: .mt-6 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Why the context on a website is important
Page titles are essential to enable all users to quickly identify the content of a website. On the one hand, pages must be marked with the `<title>` element, so that pages in browser tabs can be quickly identified. On the other hand it makes sense to give each page a content describing `<h1>` title (main title), so that people with visual impairments or with memory weaknesses can put the pages into context faster.
{: .mb-8 }

#### The following examples illustrate the importance of context:
{: .no_toc .mb-5 }

![](//placehold.it/800x400)
TBD.
{: .fs-2 .fw-800 .mb-6 }

![](//placehold.it/800x400)
TBD.
{: .fs-2 .fw-800 .mb-6 }

---

## Set titles, everywhere
That means for us as designers, titles are essential to improve the usability of a website. Therefore it makes sense to give each new section of a website or app a title that is appropriate to its content, in addition to the `<h1>` title. This has the following advantages.

- Blind users notice the change to a new section within a page and can associate the content.
- Users who navigate using the keyboard can easily skip from one section to another.
- The risk of creating misunderstandings on the site through unclear sections is minimized.

![](//placehold.it/800x400)
TBD.
{: .fs-2 .fw-800 .mb-6 }

---

## Make meaningful labels

Not only pages and sections need titles that match the content. Also for links and buttons it is important that they show the action behind them. So all users and especially blind users can skip links that are not interesting for them. 
{: .mb-8 }

#### The following examples illustrate the importance of meaningful labels:
{: .no_toc .mb-5 }

<div class="code-example" markdown="1">

[More](http://example.com/){: .btn } <br>
[Start](http://example.com/ "Start"){:target="_blank"}

For the user such labels are meaningless, even in the context of the content it is difficult to see what is behind the button or link.  It should be avoided that the user has to read additional text to understand simple buttons and links.

</div>



<div class="code-example" markdown="1">

[Learn more about accessibility](http://example.com/){: .btn } <br>
[start your project now](http://example.com/ "start your project now"){:target="_blank"}

With a content describing label it is now clear what kind of action is behind the button or link. The user can even see what is triggered by the elements without reading the content. **This is useful for people who navigate through a page with a screen reader**.
</div>

---

## Active and inactive status
It is also a matter of context if we only show certain contents of a page by interaction. The user must be able to determine the connection between trigger and appearing content at any time. Active elements should therefore always be highlighted. See also chapter [Nested content](/Accessibility-Designer-Guide/docs/Architecture/nested-content/) to get more detailed information on this topic. 
{: .mb-8 }
 

![](//placehold.it/800x400)
TBD.
{: .fs-2 .fw-800 .mb-6 }


---

##### Links
{: .no_toc }

[W3C – Page Titled](https://www.w3.org/WAI/WCAG21/Understanding/page-titled.html "W3C – Page Titled"){:target="_blank"} <br>
[W3C – Section Headings](https://www.w3.org/WAI/WCAG21/Understanding/section-headings.html "W3C – Section Headings"){:target="_blank"} <br>
[W3C – Link Purpose](https://www.w3.org/WAI/WCAG21/Understanding/link-purpose-link-only.html "W3C – Link Purpose"){:target="_blank"} <br>
[W3C – Accordion](https://www.w3.org/TR/wai-aria-practices/examples/accordion/accordion.html "W3C – Accordion"){:target="_blank"} <br>

