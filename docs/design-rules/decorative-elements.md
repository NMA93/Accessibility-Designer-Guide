---
layout: default
title: Decorative elements
parent: Design rules
nav_order: 8
---

# Decorative elements
{: .no_toc }
{: .fs-9 }

Decorative elements without actual use are often used to give a website an individual look. However, certain rules must be observed to ensure that a website can be designed barrier-free.
{: .fs-6 .fw-300 }

Aesthetic and minimalist design
{: .label .label-black }

<img src="{{ '/assets/images/hero/decorative.png' | prepend: site.baseurl }}" alt="Title Picture Decorative elements" title="Title Picture Decorative elements"/>
{: .mt-6 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


---

## What problems can occur with decorative elements?
Some people find it difficult to concentrate because decorative elements can interrupt their user experience. Decorative elements, if used incorrectly, can also disturb screen readers and keyboard navigation.

---

## Decorative elements are not bad
First of all, decorative elements are not generally bad. You can structure a website into sections or highlight and bundle certain information.


---

## Do not disturb the UI
If decorative elements are used, they must under no circumstances disturb the UI. The following rules must be observed.

- Do not use a primary colour which is in use on the page.
- Use decorative elements only rarely.
- Do not make information dependent on decorative elements.
- Do not distract from the actual focus.


---

## Do not override other functions
Sometimes decorative elements are the heart of a website or app and should be presented accordingly. The following should not be the case:

### Screen freeze
A decorative element or animation should not "freeze" the screen and draw full attention to the element. Users can lose their orientation, and users with disabilities cannot understand the process.

### Navigation and ARIA
Important: When decorative elements are used, they must not affect the experience when using screen readers or navigating with the keyboard.

Adding `aria-hidden="true"` to an element removes that element and all of its children from the accessibility tree. This can improve the experience for assistive technology users by hiding:

- purely decorative content, such as icons or images
- duplicated content, such as repeated text
- offscreen or collapsed content, such as menus

---

##### Links
{: .no_toc }

[W3C – ARIA](https://www.w3.org/WAI/standards-guidelines/aria/ "W3C: WAI-ARIA Overview"){:target="_blank"} <br>
[Developer Mozilla ARIA](https://developer.mozilla.org/en-US/docs/Web/Accessibility/ARIA/ARIA_Techniques/Using_the_aria-hidden_attribute "Developer Mozilla ARIA"){:target="_blank"}
