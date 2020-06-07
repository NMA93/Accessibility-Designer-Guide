---
layout: default
title: Typography
parent: Design rules
nav_order: 2
---

# Typography
{: .no_toc }
{: .fs-9 }

For centuries, typefaces have been refined by type designers, typographers, and designers. Many specifications that work for print can also be transferred to the web and can improve the usability and accessibility of a page.
{: .fs-6 .fw-300 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## For which users can incorrect typography be a problem?
If the font sizes are too small, the character spacing is too large and the semantics are ignored, this affects the user.

- Users with limited vision cannot read the content
- Users who have problems reading find it difficult to find their way
- Users with concentration problems are more quickly distracted by their surroundings due to the challenging typography

---

## Print also works digitally

For centuries, typefaces have been refined by type designers, typographers and designers. Many specifications that work for **print can also be transferred to the web** and can increase the usability of a page.


## Fonts sizes
From classical typography we know a clear classification of font sizes, **3 categories have been established**:

### For print

|  Use of the font  | Size oft the font   |
| --------------------------- |:------------------------------: | 
| The consultation size<br> *(annotations, margin notes, captions, lexicon entries)*  |  6 – 8 points | 
| The reading size <br>  *(larger texts)*   | 9 – 12 points   |
| The sight size <br>  *(titels*   | 14 – 28 points  |

This rule has proven itself and helps to structure texts in print in a way that is pleasing to the eye. Of course, this rule can also be broken, but to break a rule, one must first know it. 

I always have this rule in mind when I have to develop font sizes for digital products. They are well suited to create a harmonious typeface on the web, but point values cannot simply be adopted 1:1 for pixel values. The following rule serves as a good basis for a typographic system:

### For web

|  Use of the font  | Size oft the font   |
| --------------------------- |:------------------------------: | 
| The consultation size |  13 – 14px | 
| The reading size  | 16 – 20px  |
| The sight size | 24px and more  |

In general, fonts on the Web should not be smaller than 13px, but if this should happen, it is mostly decorative elements that do not serve the UI or there must be a really good reason to fall below this value.

---

## Line height

A carefully chosen line height helps all users to understand texts faster. The eye can jump from one line to the next faster. The line height varies from font to font and depends on the line length and the visual appearance of the font. However, there are certain basic rules that can help to define a line height that is comfortable for the eye.

- As a rule, the line height should be 120% of the font size, which means at least 12px line height for a 10px font. 
- The line height should always be clearly larger than the word spacing.

<div id="container1">
 <!-- The before image is first -->
 <img src="{{ '/assets/images/typo/lineheight_x.png' | prepend: site.baseurl }}" alt="In this picture the line height is chosen too small."/>
 <!-- The after image is last -->
 <img src="{{ '/assets/images/typo/lineheight.png' | prepend: site.baseurl }}" alt="In this picture the line height is chosen correctly."/>
</div>
{: .mb-3 }

A carefully chosen line height makes it easier for all users to read the text. On the left side the line height is too small, on the right side the line height is chosen correctly.
{: .fs-3 .mb-6 }

---

## Text width

The web is often very generously designed and the complete viewport width is often used.  However, a certain part of a website should have clear limitations, and this includes copy text. If the width is too large and the number of characters per line is too high, the eye loses its orientation. This makes it difficult to read texts, not only for people with disabilities. The following example shows this clearly:

<img src="{{ '/assets/images/typo/linewidth_x.png' | prepend: site.baseurl }}" alt="In this picture Wikipedia is shown, which lets the texts run almost over the whole width of the viewport."/>
On [wikipedia](https://www.wikipedia.com "wikipedia.com"){:target="_blank"} the line width is much too wide. It is often very uncomfortable for the reader to read this text.
{: .fs-3 .mb-6 }

In print, the rule is 60 – 80 characters per line. I personally like to have a value of 500 – 700 pixels for the text in width on a website. This is quite close to the rule for printing. The font size and font type also affects this value. In the end it is a combination of all values that leads to a harmonious and pleasantly readable typeface.

<img src="{{ '/assets/images/typo/linewidth.png' | prepend: site.baseurl }}" alt="In this image the text width is reduced to 600px, in comparison to the previous image the readability is better."/>
If the line width would be reduced to max. 600px as in this example, the readability would be massively improved. 
{: .fs-3 .mb-6 }


|  Device | Width  |
| --------------------------- |:------------------------------: | 
| Desktop |  500 – 700px or 60 - 80 characters per line | 
| Tablet  | 500 – 700px or 60 – 80 characters per line   |
| Mobile | full width  |

---

## Colors
According to the [W3C](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html/ "W3C guidelines")  guidelines, the contrast of text of normal size (approx. 13px - 17px) must have a contrast ratio of at least 4.5:1. From 18px and larger font sizes, the text must have a contrast ratio of at least 3:1.

|  Font size | Contrast  |
| --------------------------- |:------------------------------: | 
| 13 – 17px |  4.5:1 | 
| 18px +  | 3:1 |

There are countless tools for checking the contrast of elements and text, one of my favourite tools is the [Colour Contrast Analyser](https://developer.paciellogroup.com/resources/contrastanalyser/ "Colour Contrast Analyser Tool") from the paciello group.


Check [Colours](/Accessibility-Designer-Guide/docs/design-rules/colours/ "Colour chapter") to learn more about colours and contrast.

---


## Levels of the titles
To give a page structure, it is important to have typographic levels. We distinguish two types of structuring. The visual structure and the technical structure.

### Visual semantic structuring
In typography, text has always been structured by semantic design and optimized for the reader. As an example we can look at a text without any markup. We see in this case a simple block, without any differentiation in itself. 
{: .mb-6 }

Quis eleifend quam adipiscing vitae. Cras sed felis eget velit. Magna ac placerat vestibulum lectus mauris ultrices eros in cursus. Montes nascetur ridiculus mus mauris vitae ultricies. Ac turpis egestas sed tempus urna et. Pellentesque sit amet porttitor eget dolor morbi non. Ipsum faucibus vitae aliquet nec. 
{: .code-example .mb-6  }

By adding different sizes and markings in the weight of the font now the text is semantically structured. The appearance of the title also gives it the meaning of a title. The same applies to the basic text, which is recognized as basic text by its appearance.
{: .mb-6 }

**Quis eleifend quam adipiscing vitae.**<br>
Cras sed felis eget velit. Magna ac placerat vestibulum lectus mauris ultrices eros in cursus. Montes nascetur ridiculus mus mauris vitae ultricies. Ac turpis egestas sed tempus urna et. Pellentesque sit amet porttitor eget dolor morbi non. Ipsum faucibus vitae aliquet nec. 
{: .code-example .mb-6  }

To ensure that there is enough visual structure on a page, the typography must have gradations that are recognizable to the eye.

# h1 Lorem ipsum
{:.code-example .no_toc }
## h2 Lorem ipsum
{: .code-example .no_toc }
### h3 Lorem ipsum
{: .code-example .no_toc }
#### h4 Lorem ipsum
{: .code-example .no_toc }
##### h5 Lorem ipsum
{: .code-example .no_toc }
###### h6 Lorem ipsum
{: .code-example .no_toc }
p Lorem ipsum
{: .code-example .no_toc }

In this guide 6 gradations have been defined, which have a clear visual gradation for the eye and thus structure the page. It is important that there is a visual gradation, otherwise the page will be difficult for all users to understand.
{: .fs-3 .mb-6 }

### Technical semantic structuring
Apart from the visual distinction, there is also a technical distinction. It is important that there is a descriptive h1 title at the top of the page. A h1 title should only appear once on a page and should never be used more than once. This is important for the ranking of the website and SEO, but also for people with disabilities who depend on a screen reader. Technically there should be a gradation from h2-h6. The screenreader doesn't care if the gradation is visually correct, but we as designers do. In the best case the gradation is technically and visually the same.

<img src="{{ '/assets/images/typo/typo_semantic.png' | prepend: site.baseurl }}" alt="In this example we see how we label the main content with the h1 and then the usual gradations down to h6. While the other content starts with an h2-h6, since it is lower-level."/>
In this example we see how we label the main content with the h1 and then the usual gradations down to h6. While the other content starts with an h2-h6, since it is lower-level.
{: .fs-3 .mb-6 }

Check [semantics](/Accessibility-Designer-Guide/docs/Architecture/semantics/ "Semantics") and [context](/Accessibility-Designer-Guide/docs/Architecture/context/ "Context") to learn more about sematnics and how to structure a page.

---

## Do not use text as image
Everyone should be aware of it, and yet it keeps popping up. Text that was placed in a header image and is now available as an image (jpeg or png) on the website. A mortal sin in terms of accessibility. Screen readers have no chance of reading this text unless it is added with Alt text. However, I recommend not to do this.

---

##### Links
{: .no_toc }

[Toptal – Web typography](https://www.toptal.com/designers/typography/web-typography-infographic#:~:text=Typography%20in%20web%20design%20is,provide%20a%20pleasant%20reading%20experience. "Toptal – Web typography"){:target="_blank"} <br>
[W3C – Page Titled](https://www.w3.org/WAI/WCAG21/Understanding/page-titled.html "W3C – Page Titled"){:target="_blank"} <br>
[W3C – Section Headings](https://www.w3.org/WAI/WCAG21/Understanding/section-headings.html "W3C – Section Headings"){:target="_blank"} <br>

