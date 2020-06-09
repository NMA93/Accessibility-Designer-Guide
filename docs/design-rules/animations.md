---
layout: default
title: Animations
parent: Design rules
nav_order: 6
---

# Animations
{: .no_toc }
{: .fs-9 }

Animations and transitions are a popular way to give a page or app a special touch. However, there are some accessibility rules to follow.
{: .fs-6 .fw-300 }

Consistency and standards
{: .label .label-black }

<img src="{{ '/assets/images/hero/animation.png' | prepend: site.baseurl }}" alt="Title Picture Animations" title="Title Picture Animations"/>
{: .mt-6 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


---

## The problem with animations
Moving or blinking elements can attract the attention of users, but they can also distract them. In extreme cases, someone may have a seizure or physical reaction to an animation. Therefore, it is important to know the WCAg standards for animation. Warnings alone are not enough, because they can be overlooked.
{: .mb-8 }

#### For the following users hectic animations can be problematic:
{: .no_toc .mb-5 }

- People with lack of concentration.
- People suffering from epilepsy.
- People who have impaired vision and therefore do not notice the animations pointing to something.

---

## Blinking and hectic animations
Animations on a website should not be hectic or blinking fast. The [W3C – Three Flashes](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes-or-below-threshold "W3C – Three Flashes"){:target="_blank"} guidelines prescribe the following rule. Content should not blink more than 3 times per second. This prevents the animation from triggering a seizure or physical reaction.

---

## Let people control motion effects
Automatic playing of videos and animations should never be used. A control button should always be used. The user should always have the possibility to trigger animations or videos by himself.

### Reduce Motion 
{: .no_toc }
For example, Apple offers a "Reduce Motion" mode so that users can use an app without restrictions.Apple recommends the following specifications:

- Tighten springs to reduce bounce effects or track 1:1 with the user’s finger
- Avoid animating depth changes in z-axis layers
- Avoid animating into or out of blurs
- Replace a slide with a fade to avoid motion

Source: [Apple – Motion](https://developer.apple.com/design/human-interface-guidelines/accessibility/overview/appearance-effects/#motion "Apple – Motion"){:target="_blank"}

---

## Do not make content dependent on animations
An app or website should always be operable without animations.
{: .mb-8 }

#### Attention must be paid to the following:

- Do not nest content in animation so users have limited time to read it.
- Do not combine essential interactions with hectic animations.
- Animations should be used carefully and have a consistent language throughout the system.

---


## Animations do not have to be bad
Supporting animations can help users to find their way around a system easily. A good example is the Apple toolbar in MacOS. By gently enlarging the tools, attention is drawn to the active tool. Another good example are "tutorial" animations that help users.

<video width="100%" height="auto" controls>
    <source src="{{ '/assets/videos/sbb.mp4' | prepend: site.baseurl }}">
</video>

In this example of the [SBB](https://sbb.ch/ "SBB"){:target="_blank"} app, a useful animation explains the app to the user.
{: .fs-3 .mb-6 }



---

##### Links
{: .no_toc }

[W3C – Three Flashes](https://www.w3.org/WAI/WCAG21/Understanding/three-flashes-or-below-threshold "W3C – Three Flashes"){:target="_blank"} <br>
[W3C – Seizures and Physical Reactions](https://www.w3.org/WAI/WCAG21/Understanding/seizures-and-physical-reactions "W3C – Seizures and Physical Reactions"){:target="_blank"} <br>
[W3C – Seizures and Physical Reactions](https://www.w3.org/WAI/WCAG21/Understanding/seizures-and-physical-reactions "W3C – Seizures and Physical Reactions"){:target="_blank"} <br>
[Apple – Motion](https://developer.apple.com/design/human-interface-guidelines/accessibility/overview/appearance-effects/#motion "Apple – Motion"){:target="_blank"}