---
layout: default
title: Colours
parent: Design rules
nav_order: 1
---

# Colours
{: .no_toc }
{: .fs-9 }

When it comes to colours, many websites die in beauty. Often CI colours for print are taken over 1:1 into the web and this does not always work very well for people with impaired vision.
{: .fs-6 .fw-300 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## It affects more people than you think

According to [WHO](https://www.who.int/news-room/fact-sheets/detail/blindness-and-visual-impairment/ "WHO Blindness and vision impairment report"){:target="_blank"} in 2020 there are 2.2 billion people with impaired vision. Of these, 300 million people are affected by colour blindness in various forms. And for this reason, designers should definitely think about colors and contrasts. **With little effort, the accessibility of a page can be massively improved**. 

<div id="container1">
 <!-- The before image is first -->
 <img src="{{ '/assets/images/heuristics/flexibility.png' | prepend: site.baseurl }}" alt="In this example the common shortcuts of programs are shown, these can be used via the keyboard or via the navigation." title="In this example the common shortcuts of programs are shown, these can be used via the keyboard or via the navigation."/>
 <!-- The after image is last -->
 <img src="{{ '/assets/images/heuristics/minimalism.png' | prepend: site.baseurl }}" alt="In this picture you can see a login screen reduced to the minimum of ui-elements." title="In this picture you can see a login screen reduced to the minimum of ui-elements."/>
</div>

<script>
$(function(){
  $("#container1").twentytwenty();
});
</script>

---

## Give your site enough contrast

According to the [W3C](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html/ "W3C guidelines")  guidelines, the contrast of text of normal size (approx. 13px - 17px) must have a contrast ratio of at least **4.5:1**. From 18px and larger font sizes, the text must have a contrast ratio of at least **3:1**.

Graphic objects and UI components should generally have a contrast ratio of **3:1**.

There are countless tools for checking the contrast of elements and text, one of my favourite tools is the [Colour Contrast Analyser](https://developer.paciellogroup.com/resources/contrastanalyser/ "Colour Contrast Analyser Tool") from the paciello group.

---

## Do not make information dependent on their colour

To understand what exactly is meant here, let's look at a typical example of a common error of information and dependence on colour. Everyone knows system status messages or error messages. 

![](//placehold.it/800x200)

Users with a common form of colour blindness, for example the inability to distinguish between the colours red and green, see this example as follows.

![](//placehold.it/800x200)

By adding an icon and text, the colour dependency is resolved and the user knows more quickly what this scenario is about.

![](//placehold.it/800x200)