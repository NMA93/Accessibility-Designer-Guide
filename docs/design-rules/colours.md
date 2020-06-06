---
layout: default
title: Colours
parent: Design rules
nav_order: 1
---

# Colours
{: .no_toc }
{: .fs-9 }

When it comes to colors, many brands prescribe a color palette based on the existing ci. However, if the colours are not optimised for the web, there is a risk of accessibility problems.
{: .fs-6 .fw-300 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## It affects more people than you think

According to [WHO](https://www.who.int/news-room/fact-sheets/detail/blindness-and-visual-impairment/ "WHO Blindness and vision impairment report"){:target="_blank"} in 2020 there are 2.2 billion people with impaired vision. Of these, 300 million people are affected by colour blindness in various forms. And for this reason, designers should definitely think about colors and contrasts. With little effort, the accessibility of a page can be massively improved.
{: .mb-5 }

#### Colors that do not comply with an accessible standard may be a problem for following users:
{: .no_toc }

- People who suffer from a form of colour blindness
- People with impaired vision
- Not enough contrast affects all users

---

## Give your site enough contrast

According to [W3C](https://www.w3.org/TR/UNDERSTANDING-WCAG20/visual-audio-contrast-contrast.html/ "W3C guidelines")  guidelines, the contrast of small text size must have a contrast ratio of at least 4.5:1. From 24px and larger font sizes the text must have a contrast ratio of at least 3:1. Graphic objects and UI components should generally have a contrast ratio of 3:1.
{: .mb-5 }

| Level AA minimum contrast   | Level AAA minumum contrast      |
| --------------------------- |:------------------------------: | 
| small text (16px, 4.5:1)    |  small text (16px, 7:1)         |
| large text (24px – 3:1)     | large text (24px – 4.5:1)       |

There are countless tools for checking the contrast of elements and text, one of my favourite tools is the [Colour Contrast Analyser](https://developer.paciellogroup.com/resources/contrastanalyser/ "Colour Contrast Analyser Tool") from the paciello group.
{: mt-6. .mb-6 }

#### The following example shows what effect a carefully chosen contrast has on the page:
{: .no_toc .mb-3 }

<div id="container1">
 <!-- The before image is first -->
 <img src="{{ '/assets/images/color/contrast-none.png' | prepend: site.baseurl }}" alt="In this picture you can see a User Interface (UI) which is not conform to the WCAG standard."/>
 <!-- The after image is last -->
 <img src="{{ '/assets/images/color/contrast-aa.png' | prepend: site.baseurl }}" alt="In this picture you can see a User Interface (UI) which is conform to the WCAG AA standard."/>
</div>
{: .mb-3 }

On the left side, the User Interface (UI) does not conform to any Web Content Accessibility Guidelines (WCAG) standard, while on the right side it conforms to the WCAG AA standard.
{: .fs-3 .mb-6 }

---

## Do not make information dependent on their colour
To ensure that visually impaired users can see all information on a page, it is important not to make the information dependent on a colour.s

![](//placehold.it/800x200)

---

## How to create a barrier-free colour scheme?
Now that we know the basic rules, it is time to apply them in practice. Not so many steps are necessary to create a barrier-free colour scheme.

### Define the shades of gray
Grey tones are essential in almost every system. They are used for backgrounds or fonts. 3 different grey tones form a good basis for a colour system.

#### Define the font color
{: .no_toc .mb-3 }
The font colour is usually the darkest shade of grey that we use. It must have a contrast of at least 7:1 or more.

<img src="{{ '/assets/images/color/colour_step_1.png' | prepend: site.baseurl }}" alt="In this picture the password was entered incorrectly. The password field is marked red and a label indicates that the password is wrong."/>
{: .mb-6 }


#### Define the brightest grey tone
{: .no_toc .mb-3 }
Once the font color is selected, we define the brightest possible tone for the gray we want to use as the font. This color must not be less than the contrast value of 3:1.

<img src="{{ '/assets/images/color/colour_step_2.png' | prepend: site.baseurl }}" alt="In this picture the password was entered incorrectly. The password field is marked red and a label indicates that the password is wrong."/>
{: .mb-6 }

#### Find the middle
{: .no_toc .mb-3 }
Now we look for the middle, with a contrast ratio of 4.5:1.

<img src="{{ '/assets/images/color/colour_step_3.png' | prepend: site.baseurl }}" alt="In this picture the password was entered incorrectly. The password field is marked red and a label indicates that the password is wrong."/>

Now we have defined 3 colors in our color system which are accessible for the text. This gives us the possibility to mark a primary, secondary and tertiary text.
{: .mb-6 }

### Define a background
Now we need a background, we have white, because we know that this color works for all 3 colors. But we need a grey background in the design to distinguish certain sections.

<img src="{{ '/assets/images/color/colour_step_4.png' | prepend: site.baseurl }}" alt="In this picture the password was entered incorrectly. The password field is marked red and a label indicates that the password is wrong."/>

We only use tertiary text on a white background, which means we have to make sure that we get enough contrast to our background for the primary and secondary text. The contrast value of 4.5:1 is the minimum contrast.

#### Define the colors
With colours, the whole thing becomes a bit more complex, we can't just change the opacity, we have to find and match certain colour values. That's a process that can take some time, but it's worth it.

<img src="{{ '/assets/images/color/colour_step_5.png' | prepend: site.baseurl }}" alt="In this picture the password was entered incorrectly. The password field is marked red and a label indicates that the password is wrong."/>

First we define the main color and make sure that there is enough contrast. It is useful to define an additional background, making sure that it has enough contrast to the black primary text and our defined color.


## But what if the customer specifies the colours?