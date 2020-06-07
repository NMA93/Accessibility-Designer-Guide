---
layout: default
title: Targetsize
parent: Design rules
nav_order: 5
---

# Targetsize
{: .no_toc }
{: .fs-9 }

The target size of buttons, links and other clickable elements is an important factor when it comes to accessibility. But what needs to be considered?
{: .fs-6 .fw-300 }

Consistency and standards
{: .label .label-black }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


---

## What is the problem with the target size?
Some people find it difficult to activate small buttons because of their age or disability. As designers, we have to follow standards so that people have the opportunity to use them on all devices.
{: .mb-8 }

#### A small target size could be a problem for the following users:
{: .no_toc .mb-5 }

- People with a hand tumor or injured hands.
- People with visual impairment.
- Users who only have one hand available to operate a device.


---

## Give clickable elements enough space
In order for systems to be able to operate with disabilities, it is important to create enough space for clickable elements. This means that, in addition to a comfortable target size, the corresponding margin, i.e. the space around it, must also be included.

<img src="{{ '/assets/images/targetsize/target.png' | prepend: site.baseurl }}" alt="For example an icon can be placed at 24px × 24px, with the space around the icon we still get a target size of at least 48px."/>
For example an icon can be placed at 24px × 24px, with the space around the icon we still get a target size of at least 48px.
{: .fs-3 .mb-6 }

---

## Basic rule
According to the [W3C – Target size](https://www.w3.org/WAI/WCAG21/Understanding/target-size "W3C – Target Size"){:target="_blank"} the target size of interaction elements must be at least 44px to 44px. Personally, I believe that this size is still rather at the minimum. [Android](https://developers.google.com/web/fundamentals/accessibility/accessible-styles#multi-device_responsive_design "Android"){:target="_blank"} recommend a target size of 48px to 48px, which is a more convenient target size.

| Device  | Targetsize  |
|---------|-------------|
| Mobile  | 48px × 48px   |
| Desktop | 48px × 48px   |

Excepted from this rule are text links in the content, since these are part of the content itself.


---

## Mobile and Desktop
The differences between desktop and mobile are minimal, the target size does not change. Only the margin can be a slightly tighter on the desktop, since Mobile, in difference to the desktop, is navigated by touch. However, the elements should be left enough room for interaction here as well.

---

##### Links
{: .no_toc }

[W3C – Target size](https://www.w3.org/WAI/WCAG21/Understanding/target-size "W3C – Target Size"){:target="_blank"} <br>
[Android – Multi-device responsive design](https://developers.google.com/web/fundamentals/accessibility/accessible-styles#multi-device_responsive_design "Android – Multi-device responsive design"){:target="_blank"}
