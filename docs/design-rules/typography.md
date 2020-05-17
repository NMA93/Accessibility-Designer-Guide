---
layout: default
title: Typography
parent: Design rules
nav_order: 2
---

# Typography
{: .no_toc }
{: .fs-9 }

Fonts affect the appearance of a website like no other element. It is therefore not surprising that they also have a great influence on usability.
{: .fs-6 .fw-300 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Print also works digitally

For centuries, typefaces have been refined by type designers, typographers and designers. Many specifications that work for **print can also be transferred to the web** and can increase the usability of a page.


## Fonts sizes
From classical typography we know a clear classification of font sizes, **3 categories have been established**:

### For print
- The consultation size: **6 - 8 point** *(annotations, margin notes, captions, lexicon entries)*
- The reading size: **9 - 12 point** *(larger texts)*
- The sight size: **14 - 28 point** *(titles)*

This rule of thumb has proven itself and helps to structure texts in print in a way that is pleasing to the eye. Of course, **this rule can also be broken, but to break a rule, one must first know it**. 

Personally, I always have this rule in mind when I have to develop font sizes for digital products. They are well suited to create a harmonious typeface on the web, but point values cannot simply be adopted 1:1 for pixel values. The following rule serves as a **good basis for a typographic system**:

> ### For web
- The consultation size: **13 – 14px**
- The reading size: **16 - 20px**
- The sight size: **ca. 24px – to the top without limit**

In general, **fonts on the Web should not be smaller than 13px**, but if this should happen, it is mostly decorative elements that do not serve the UI or there must be a really good reason to fall below this value.

---

## Line height

A carefully chosen line height not only helps users with disabilities to understand text faster. The line height varies from font to font and is dependent on the line length and the visual appearance of the font. Still, there are certain basic rules that can help to define a line height that is comfortable for the eye.

- As a rule of thumb, the line height should be **120% of the font size**, which means at least **12px line height for a 10px font**. 
- The line height should always be **clearly larger than the word spacing**.

---

## Text width

The web is often very generously designed and the complete viewport width is often used.  However, a certain part of a website should have clear limitations, and this includes copy text. If the width is too large and the number of characters per line is too high, the eye loses its orientation. This makes it difficult to read texts, not only for people with disabilities. The following example shows this clearly:

![](//placehold.it/800x200)

In print, a rule of thumb is **60 – 80 characters per line**. I personally like to have a value of **500 – 700 pixels** for copy text in the width on a website. This comes pretty close to the rule for print Depending on font and font size. In the end it is a combination of all values that results in a harmonious and pleasantly readable typeface.

![](//placehold.it/800x200)


### Width values
- Desktop: **500 – 700px**
- Tablet: **500 – 700px**
- Mobile: **full width**

## Colors
According to the [W3C](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html/ "W3C guidelines")  guidelines, the contrast of text of normal size (approx. 13px - 17px) must have a contrast ratio of at least **4.5:1**. From 18px and larger font sizes, the text must have a contrast ratio of at least **3:1**.

There are countless tools for checking the contrast of elements and text, one of my favourite tools is the [Colour Contrast Analyser](https://developer.paciellogroup.com/resources/contrastanalyser/ "Colour Contrast Analyser Tool") from the paciello group.


Check [Colours](https://nma93.github.io/Accessibility-Designer-Guide/02-General%20specifications/03-Colours// "Colour chapter") to learn more about colours and contrast.


## Levels of the titles
TBD

## Do not use text as image
Everyone should be aware of it, and yet it keeps popping up. Text that was placed in a header image in Photoshop and is now available as an image (jpeg or png) on the website. A mortal sin in terms of accessibility. Screen readers have no chance of reading this text unless it is added with alt text. However, I recommend not to do this.
