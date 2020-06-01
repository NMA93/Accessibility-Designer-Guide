---
layout: default
title: Navigation
parent: Architecture
nav_order: 2
---

# Navigation
{: .no_toc }
{: .fs-9 }

The navigation is the heart of many websites and apps. If mistakes are made there, the user experience is significantly affected. But this does not have to be the case.
{: .fs-6 .fw-300 }

Consistency and standards
{: .label .label-black }
User control and freedom
{: .label .label-black }
Aesthetic and minimalist design
{: .label .label-black }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What problems can be caused by the navigation?
If certain rules in a navigation are not followed, users can lose their orientation within the page. Content may be overlooked or not found, and there may also be a feeling that your target group is not being addressed. 
{: .mb-6 }

#### An inconsistent and not well thought out navigation can be a problem for the following users:
{: .no_toc .mb-5 }

- People with a visual impairment
- People who are blind and navigate with a screen reader
- People who navigate through the site with the keyboard

In order to make it as easy as possible for these user groups to navigate within the site, it makes sense to observe the following rules.

---

## Show me the easiest way!

The navigations are basically only intended to help the user to find his way around the website. Therefore, as a designer, you should not reinvent the pattern in terms of navigation. Given standards help to create a solid navigation, and if the designer is aware of the rules, visually appealing results can be achieved within this framework.


### Show me the site architecture

Not only the site architecture should follow a hierarchy as we learned in chapter <a href="/Accessibility-Designer-Guide/docs/Architecture/website-architecture/"> Website architecture</a>, also the navigation should do so. Optimally, the navigation reflects the page architecture in a simplified form. This helps the user to get an overview of the content.
{: .mb-6 }

<div id="container1">
 <!-- The before image is first -->
 <img src="{{ '/assets/images/navigation/flow.png' | prepend: site.baseurl }}" alt="In this example we see a clear hierarchical structure of the pages which is divided by 4 category landing pages."/>
 <!-- The after image is last -->
 <img src="{{ '/assets/images/navigation/navigation_structure.png' | prepend: site.baseurl }}" alt="In this picture you see a page navigation, which displays the architecture of the website."/>
</div>
{: .mb-3 }

The site architecture should be displayed in the navigation, as shown in this example.
{: .fs-3 .mb-6 }

### Where am I
Show the user in the navigation where he is on the page. By marking the active menu items, the orientation on the page is noticeably improved for users.

<img src="{{ '/assets/images/navigation/navigation_where.png' | prepend: site.baseurl }}" alt="In this example the active menu item is marked."/>
In this example the active menu item is marked.
{: .fs-3 .mb-6 }

### Where do I come from
But not only the active page should be highlighted, also higher-level pages in the navigation should be highlighted. In this way, the user is always aware of where he or she has come from and where he or she is currently located.

<img src="{{ '/assets/images/navigation/navigation_from.png' | prepend: site.baseurl }}" alt="In this example the active menu items are marked. This is applied consistently on all levels within the navigation. The user has a clear overview of where he is."/>
In this example the active menu items are marked. This is applied consistently on all levels within the navigation. The user has a clear overview of where he is.
{: .fs-3 .mb-6 }

### Where do I want to go
Highlight navigation points that are in the focus of the user. This helps users navigate through the page to find their way around.

<video width="100%" height="auto" controls>
    <source src="{{ '/assets/videos/hover.mp4' | prepend: site.baseurl }}">
</video>

In this example from [Google Material Design](https://material.io/ "Google MAterial Design"){:target="_blank"}  we see how the hover state is clearly indicated in the navigation.
{: .fs-3 .mb-6 }

Often designers forget that the focus can also be designed. This is important for people who navigate the website with the keyboard. For better orientation of the user, the focus status differs in the visuality from the active menu items and hover. See <a href="/Accessibility-Designer-Guide/docs/Architecture/keyboard-friendly/"> Keyboard friendly.</a>

<img src="{{ '/assets/images/navigation/focus_sbb.png' | prepend: site.baseurl }}" alt="In this picture we see an example of a focus state with a shadow, which clearly distinguishes it from the elements."/>
On [sbb.ch](https:sbb.ch "sbb.ch"){:target="_blank"} the focus state has been specially marked with a shadow, which clearly distinguishes it from the active menu items (Business customers) and the hover status.
{: .fs-3 .mb-6 }

---

## Breadcrumbs
In addition to navigation, breadcrumbs are excellent for showing the way of a user. Many designers tend to remove breadcrumbs for aesthetic reasons. I have a clear opinion on this and think this is a mistake. For complex websites with several navigation levels, they can make navigation a lot easier.

<img src="{{ '/assets/images/navigation/navigation_sbb_breadcrumbs.png' | prepend: site.baseurl }}" alt="In this picture we see breadcrumbs that have been designed with a drop-down function and thus function as a menu."/>
On [sbb.ch](https:sbb.ch "sbb.ch"){:target="_blank"} the breadcrumbs were extended with a kind of menu function. This makes the breadcrumbs especially useful for quickly switching between the subpages of a topic using the keyboard.
{: .fs-3 .mb-6 }


---

## Consistency
UI components with the same function should always have the same appearance. Therefore, the navigation within the entire page should have the same visual appearance and language. It can happen that a page has visually different sections, but the navigation should not be affected by this.

---

## Footer navigation
Footer navigation is suitable for making pages accessible in various ways. The footer navigation should give the user an overview of the most important menu items. Useful links such as "Contact" and "Language selection" are quickly accessible.

### Benefits of footer navigation
Not only important tasks can be reached via Footer naviation. The footer navigation also creates the visual end of a page. The repetition pattern at the end of a page gives users with disabilities an additional indication.

<img src="{{ '/assets/images/keyboard/footer.png' | prepend: site.baseurl }}" alt="Apple lists the navigation again in the footer and also includes general settings and contact links there."/>
Apple lists the navigation again in the footer and also includes general settings and contact links there. [Apple](https://www.apple.com/ "Apple.com"){:target="_blank"}
{: .fs-3 .mb-6 }

---


##### Links
{: .no_toc }

[W3C – Bypass Blocks](https://www.w3.org/WAI/WCAG21/Understanding/bypass-blocks "W3C – Bypass Blocks"){:target="_blank"} <br>
[W3C – Page Titled](https://www.w3.org/WAI/WCAG21/Understanding/page-titled.html "W3C – Page Titled"){:target="_blank"} <br>
[W3C – Section Headings](https://www.w3.org/WAI/WCAG21/Understanding/section-headings.html "W3C – Section Headings"){:target="_blank"} <br>
[W3C – Link Purpose](https://www.w3.org/WAI/WCAG21/Understanding/link-purpose-link-only.html "W3C – Link Purpose"){:target="_blank"} <br>
[W3C – Multiple Ways](https://www.w3.org/WAI/WCAG21/Understanding/multiple-ways "W3C – Multiple Ways"){:target="_blank"} <br>
[W3C – Focus Visible](https://www.w3.org/WAI/WCAG21/Understanding/focus-visible "W3C – Focus Visible"){:target="_blank"} <br>
[W3C – Location](https://www.w3.org/WAI/WCAG21/Understanding/location "W3C – Location"){:target="_blank"} <br>