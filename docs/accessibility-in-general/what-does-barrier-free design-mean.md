---
layout: default
title: What does barrier-free design mean
parent: Accessibility in general
nav_order: 2
---

# What does barrier-free design mean
{: .no_toc }
{: .fs-9 }

In recent years, barrier-free design has become more and more a topic when it comes to the conception, design and implementation of digital solutions. But what exactly is meant by this?
{: .fs-6 .fw-300 }

<img src="{{ '/assets/images/meaning.png' | prepend: site.baseurl }}" alt="Title Picture what does barrier-free design mean" title="Title Picture what does barrier-free design mean"/>

---


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Understanding accessibility

[Google Material Design](https://material.io/design/usability/accessibility.html#understanding-accessibility "Google Material Design"){:target="_blank"} defines accessible design as follows. "Accessibility in design enables users with different skills to navigate, understand and use your interface." I think that sums up the area of accessible design quite well. It's about not excluding people from digital solutions.

### Users with disabilities
When people think of barrier-free design, many think of people with disabilities first. But it is not always only people with disabilities who depend on barrier-free design. Designing Interactive Systems’ author, David Benyon, offers five reasons an inaccessible product excludes users:

- Physical – takes too much strength to use.
- Conceptual – has hard-to-understand instructions.
- Economic – is too expensive.
- Cultural – users can’t understand metaphors regarding product interaction.
- Social – on joining a group, users don’t understand that group’s social conventions.

Source: [Designing Interactive Systems](https://www.pearson.ch/HigherEducation/Pearson/EAN/9781447920113/Designing-Interactive-Systems "Designing Interactive Systems"){:target="_blank"}
{: .fs-3 .mb-6 }

---

## Assistive technology
People with disabilities need assistive technologies to consume content on websites or in apps. Screen readers or keyboard navigation are certainly the most common means to do this.
{: .mb-6 }

### Screenreader
{: .no_toc }
Screenreader is a program that enables users with visual impairments to read content on a website. This can be done using a Braille display or by reading the content aloud. Screenreaders not only visualize and describe the visible content of a page, but also describe hidden content and elements. Descriptions for images and icons can be seen as examples. Content can be labelled to improve the screen reader experience. See chapter [Semantics]({{ site.baseurl }}{% link docs/Architecture/semantics.md "Semantics" %}) to learn more about this topic.

<img src="{{ '/assets/images/meaning/screenreader.png' | prepend: site.baseurl }}" alt="In this picture we see the Dot Mini. A smart device that can access any digital text content from websites, books, magazines, audio and even films on its own and transfer them into Braille."/>
Dot Mini is a smart device that can access any digital text content from websites, books, magazines, audio and even films on its own and transfer them into Braille. [dotincorp](https://www.dotincorp.com/dot-mini "dotincorp"){:target="_blank"}
{: .fs-3 .mb-6 }

### Keyboard
{: .no_toc }
Some people find it easier to operate a system using a keyboard. This may be the case if the hands are injured or if there are other physical limitations. Navigation using the keyboard allows you to jump from anchor to anchor and from section to section.  However, there is much more to a pleasantly usable page than just jumping from one section to another using the keyboard. Hidden keyboard menus and links for skipping sections help to make using the keyboard more comfortable. See chapter [Keyboard friendly](/Accessibility-Designer-Guide/docs/Architecture/keyboard-friendly/ "Keyboard friendly"){:target="_blank"} to learn more about this topic.

---

##### Links
{: .no_toc }

[Google Material Design](https://material.io/design/usability/accessibility.html#understanding-accessibility "Google Material Design")
