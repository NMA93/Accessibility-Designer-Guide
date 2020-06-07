---
layout: default
title: Consistency
parent: Design rules
nav_order: 5
---

# Consistency
{: .no_toc }
{: .fs-9 }

A consistent design that is used throughout the system gives the user a feeling of confidence when working with the system. But what exactly does this mean and what do I need to consider?
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

## The problem with inconsistent use of elements
Elements with the same appearance should always have the same function. This is important for users who are not familiar with the system or for people with disabilities. 
{: .mb-5 }

#### An inconsistent system can be a problem for the following users
{: .no_toc }

- People who are blind and navigate with a screen reader
- User with impaired vision
- Inexperienced or older users

---

## Same appearance same function
If 2 elements look the same, but trigger a different action, this leads to confusion for the user. The site may become unusable for people with disabilities.
{: .mb-5 }

<img src="{{ '/assets/images/consistency/same.png' | prepend: site.baseurl }}" alt="In this example titles are underlined, this can lead to confusion, because links in the copy text are also underlined. This can lead to problems despite colour differentiation."/>
In this example titles are underlined, this can lead to confusion, because links in the copy text are also underlined. This can lead to problems despite colour differentiation.
{: .fs-3 .mb-6 }

---

## Colours
Colours are an important design tool when it comes to the usability of a page. We can use colours to highlight interactive elements, brand the website or highlight information. It makes sense to use a strict colour system. Generally we can separate the page into 2 colour systems.  See also chapter [Colours](/Accessibility-Designer-Guide/docs/design-rules/colours/) to get more detailed informations about colours.

### Primary colours
Primary colours are essential colours in our design system. This includes colours like: Text colour, interaction colour, white and branding colour. These colours are exclusive and are only used for the intended purpose. They allow users with impaired vision to better navigate.

### Secondary colours
Secondary colours are used to design the page, for example within illustrations or graphics. But backgrounds can also be defined in this colour category. In general, it should be noted that these differ enough from the primary colours. And that they have enough contrast.

<div id="container3">
 <!-- The before image is first -->
 <img src="{{ '/assets/images/color/action_x.png' | prepend: site.baseurl }}" alt="In this picture the interaction colour is used for typography and decorative elements, therefore the call to action is overlooked."/>
 <!-- The after image is last -->
 <img src="{{ '/assets/images/color/action.png' | prepend: site.baseurl }}" alt="In this picture the call to action stands out clearly, because it has the interaction color as the only element."/>
</div>
{: .mb-3 }

This example shows why it makes sense to define a color for clickable elements. The actual main interaction is lost if the interaction color is used too often.
{: .fs-3 .mb-6 }

---

## Positionings
Certain elements have established their position on a website and should be retained. These include navigation and footer. As a general rule, it should be ensured that elements once placed are consistently placed in the same position on all other pages. This allows users with screen readers or users with disabilities to use familiar patterns.

---

## How can I achieve a consistent design?
A consistent design across all breakpoints and screens can only be achieved with a detailed design system. Even if You as ux-designer not work with other designers, it makes sense to create one. You can work on a solid basis during the whole design process.

<img src="{{ '/assets/images/heuristics/consistency.png' | prepend: site.baseurl }}" alt="The picture shows a design system." title="The picture shows a design system."/>

---

##### Links
{: .no_toc }

[W3C – Consistent Navigation](https://www.w3.org/WAI/WCAG21/Understanding/consistent-navigation "W3C – Consistent Navigation"){:target="_blank"} <br>
[W3C – Use of Color](https://www.w3.org/WAI/WCAG21/Understanding/use-of-color "W3C – Use of Color"){:target="_blank"} <br>
[W3C – Contrast](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0#contrast-minimum "W3C – Contrast"){:target="_blank"} <br>



