---
layout: default
title: Semantics
parent: Architecture
nav_order: 3
---

# Semantics
{: .no_toc }
{: .fs-9 }

The structure and dependency of the content on a website gives a product the finishing touch in accessibility.
{: .fs-6 .fw-300 }
Match between system and the real world
{: .label .label-black }
Aesthetic and minimalist design
{: .label .label-black }

<img src="{{ '/assets/images/ARIA.png' | prepend: site.baseurl }}" alt="Title Picture ARIA" title="Title Picture ARIA"/>
{: .mt-6 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is meant by semantics?

Semantics is called the theory of the meaning of signs. As designers, we can give meaning to text and other elements through their appearance or positioning. In general, the appearance should support the content and not force a meaning. The following examples illustrate this.

### Semantic in text

Everyone of us comes into contact with semantics in text. In typography, text has always been structured by semantic design and optimized for the reader. As an example we can look at a text without any markup. We see in this case a simple block, without any differentiation in itself. 
{: .mb-6 }

Quis eleifend quam adipiscing vitae. Cras sed felis eget velit. Magna ac placerat vestibulum lectus mauris ultrices eros in cursus. Montes nascetur ridiculus mus mauris vitae ultricies. Ac turpis egestas sed tempus urna et. Pellentesque sit amet porttitor eget dolor morbi non. Ipsum faucibus vitae aliquet nec. 
{: .code-example .mb-6  }

Just by adding a break we can give meaning to the content. Now we see the title and basic font within the text block.
{: .mb-6 }

Quis eleifend quam adipiscing vitae.<br>
Cras sed felis eget velit. Magna ac placerat vestibulum lectus mauris ultrices eros in cursus. Montes nascetur ridiculus mus mauris vitae ultricies. Ac turpis egestas sed tempus urna et. Pellentesque sit amet porttitor eget dolor morbi non. Ipsum faucibus vitae aliquet nec. 
{: .code-example .mb-6  }

By adding different sizes and markings in the weight of the font, we can enhance this effect. Now the text is semantically structured. The appearance of the title also gives it the meaning of a title. The same applies to the basic text, which is recognized as basic text by its appearance.
{: .mb-6 }

**Quis eleifend quam adipiscing vitae.**<br>
Cras sed felis eget velit. Magna ac placerat vestibulum lectus mauris ultrices eros in cursus. Montes nascetur ridiculus mus mauris vitae ultricies. Ac turpis egestas sed tempus urna et. Pellentesque sit amet porttitor eget dolor morbi non. Ipsum faucibus vitae aliquet nec. 
{: .code-example .mb-6  }

### Semantic in Code

In the code, the semantics are not as clearly visible to the user as we know it from print and typography. In code, semantics includes all elements on a website. Although text on the web is also semantically prepared, there are many more elements that need to be marked up, text alone is not enough. It is important to correctly label the elements. This has the following reasons:

- Semantic code can be better read by programs.
- Loading times are shortened.
- Automatic tables of contents can be created.
- The keyboard operation is easier. See <a href="/Accessibility-Designer-Guide/02-Architecture/04-keyboard%20friendly/"> Keyboard friendly.</a>
- Accessibility is made possible because screen readers can read the content.

Basically, each element on the page is given a meaning in the code that corresponds to the content or function of the element. This has several advantages, especially in terms of accessibility. The semantics in the code allows screen readers to read the meaning of individual elements, allowing people with impaired vision to navigate the page.

<video width="100%" height="auto" controls>
    <source src="{{ '/assets/videos/screenreader.mp4' | prepend: site.baseurl }}">
</video>
This page, for example, was built semantically correct, i.e. screenreaders recognize the elements and can describe them correctly.
{: .fs-3 .mb-6 }

---

## Semantic in Code (HTML5)– Cheatsheet

| HTML 5          | Meaning       |
| ------------- |:-------------:| 
| `<h1 – h6>`   | Titles in text. |
| `<header>`    | Header section oft the page. |
| `<nav>`    | With this you can mark a section of a page, which contains links for navigation. |
| `<footer>`    | Footer section oft the page. |
| `<article>` | Self-contained composition in one document. |
| `<aside>` | Content that indirectly belongs to the rest of the content, for example a dictionary of terms. |
| `<details>` | Is used to mark up additional information, for example in a dropwdown, is often used in combination with the `<summary>` element. |
| `<summary>` | Is often used to mark additional information, for example in combination with the `<details>` element. |
| `<figure>` | An element that often explains itself graphically. For example a picture. The corresponding descriptive element is the `<figcaption>` element. |
| `<figcaption>` | Describes the content of the related `<figure>` element. |
| `<main>` | This can be used to mark the primary content of a page. for a blog post this would be the main text. |
| `<mark>` | This can be used to identify highlighted text. |
| `<time>` | This can be used to mark times or specific dates in the text. |

---

## Why semantics in design helps developers
If you are a designer without any code knowledge and now think that this is the job of the developers, you are right, but also not. Correct is, it is the task of the developers to implement the code semantically correct. However, if semantic code principles are followed in the design, the implementation is much easier later in the code. The following principles should be followed:

### Structure of the page
Make sure that your design can be categorized into the common areas. Clear areas on your site simplify the structure for developers.

<img src="{{ '/assets/images/semantics/semantic_structure.png' | prepend: site.baseurl }}" alt="In this picture you can see a page that has been broken down into its semantic structure."/>
In this example clear structures can be seen on the page. If modules are designed within this structure, implementation in the code is easier later.
{: .fs-3 .mb-6 }

### Correct use of the elements
Use elements correctly and do not complicate your design unnecessarily. An example is overloaded overlays or multi-level nesting in dropdowns. 

---

##### Links
{: .no_toc }

[developer.mozilla – semantics](https://developer.mozilla.org/en-US/docs/Glossary/Semantics "developer.mozilla – semantics"){:target="_blank"} <br>
[w3schools – HTML Semantic Elements](https://www.w3schools.com/html/html5_semantic_elements.asp "w3schools – HTML Semantic Elements"){:target="_blank"} <br>
[W3C – Using semantic elements to mark up structure](https://www.w3.org/TR/WCAG20-TECHS/G115.html "Using semantic elements to mark up structure"){:target="_blank"} <br>