---
layout: default
title: Icons
parent: Design rules
nav_order: 3
---

# Icons
{: .no_toc }
{: .fs-9 }

When it comes to icons, different specifications must be observed. Not all icons are self-explanatory or designed for small applications. 
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

## Signs and communication
So that we can take a closer look at the topic of icons and analyze them for accessibility. First we have to understand what an icon is. This definition is actually not as simple as it seems. Charles S. Peirce, a philosopher of the late 19th century defined [3 basic signs](https://plato.stanford.edu/entries/peirce-semiotics/ "Stanford Encyclopedia of Philosophy – Peirce’s Theory of Signs"){:target="_blank"} in semiotics: the icon, the index and the symbol.

---

### Understanding icon
An icon resembles the object it stands for and thus establishes a connection to it. The following example illustrates this.

![](//placehold.it/800x200)
A classic icon from the field of user interface design is the mail icon. It shows a letter and creates the link to the physical letter and the sending of a message.
{: .fs-3 .mb-6 }

---

### Understanding index
An index indicates what it stands for, the classic example is smoke which stands for fire.

![](//placehold.it/800x200)
TBD.
{: .fs-3 .mb-6 }


---

### Understandning symbol
The symbol makes no clear connection to its origin. The meaning often has to be learned culturally, which means that prior knowledge is needed to understand symbols. A good example of this are religious symbols, which are not self-explanatory for all people at first go.

![](//placehold.it/800x200)
TBD.
{: .fs-3 .mb-6 }

### Understanding icons in UI
Now that we have defined the basics, it is time to transfer them into the user interface design. Icons are elementary components of user interfaces. We can label functions using established icons or simplify contents through supporting icons. In the beginning of the user interface design we tried to design these icons as close as possible to the original.
{: .mb-6 }

<img src="{{ '/assets/images/icons/system_7.png' | prepend: site.baseurl }}" alt="In this picture we see the famous System 7 from Apple. Folders look like folders and the trash can looks like a trash can." title="In this picture we see the famous System 7 from Apple. Folders look like folders and the trash can looks like a trash can."/>
In this picture we see the famous System 7 from Apple. Folders look like folders and the trash can looks like a trash can.
[Wikimedia – Apple](https://en.wikipedia.org/wiki/File:Macintosh_System_7.5.3_screenshot.png "Wikimedia – Apple"){:target="_blank"}
{: .fs-3 .mb-6 }

And now we also see that at some point we reach a limit with icons as defined by semiotics. We cannot display complex processes like a "login" or "file sharing" exactly as it is meant. That's why in the UI we rather speak of **symbols which are used as icons**. 

---
## Icons in UI
Icons in user interface design are to be considered as symbols and sometimes require prior knowledge. There are various icons that have established themselves and now stand for themselves.

- Search icon
- Navigation bars
- User icon
- Close icon

### Icon labels

If icons that are not self-explanatory are used as interaction elements, they should always have a label that explains their function.

<div id="container1">
 <!-- The before image is first -->
 <img src="{{ '/assets/images/icons/no_labels.png' | prepend: site.baseurl }}" alt="In this picture you can see a User Interface (UI) which is not conform to the WCAG standard."/>
 <!-- The after image is last -->
 <img src="{{ '/assets/images/icons/labels.png' | prepend: site.baseurl }}" alt="In this picture you can see a User Interface (UI) which is conform to the WCAG AA standard."/>
</div>
{: .mb-3 }

We see here two times the same interface, once with labels and once without. It is immediately clear that the interface with label is more user-friendly. Not only for users with disabilities it's much easier to use the interface with labels, but for all users. See also chapter [Context](/Accessibility-Designer-Guide/docs/Architecture/context/) to get more detailed informationabout meaningful labels. 

### Icons contrast
For UI components and graphical objects, [WCAG](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html/ "W3C guidelines") requires a contrast ratio of at least 3:1. If icons are used as interaction elements, for example in navigation, a contrast of 4.5:1 is recommended. Since the icons in navigation must be aligned with the navigation labels. See also chapter [Colours](/Accessibility-Designer-Guide/docs/design-rules/colours) to get more detailed information about contrast. 

There are countless tools for checking the contrast of elements and text, one of my favourite tools is the [Colour Contrast Analyser](https://developer.paciellogroup.com/resources/contrastanalyser/ "Colour Contrast Analyser Tool") from the paciello group.

### Icons for small applications
Icons are well suited to make the interface more understandable. One challenge is to design icons for all device sizes. It is recommended to adapt the icons for each viewport to ensure that they are always recognizable for all users. This helps people with visual disabilities to find their way around.
{: .mb-3 }

#### Icons are usually formatted as follows:
{: .no_toc .mb-5 }

- 32/32px ore more
- 24/24px
- 16/16px
- 8/8px for small sizes

![](//placehold.it/800x200)
TBD.
{: .fs-3 .mb-6 }

![](//placehold.it/800x200)
TBD.
{: .fs-3 .mb-6 }

---

##### Links
{: .no_toc }

[W3C – Non-text Content](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0#non-text-content "W3C – Non-text Content"){:target="_blank"} <br>
[W3C – Contrast](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0#contrast-minimum "W3C – Contrast"){:target="_blank"} <br>
[W3C – Images of Text](https://www.w3.org/WAI/WCAG21/quickref/?versions=2.0#images-of-text "W3C – Images of Text"){:target="_blank"} <br>



