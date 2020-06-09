---
layout: default
title: Support through the system
parent: Architecture
nav_order: 10
---

# Support through the system
{: .no_toc }
{: .fs-9 }

People with disabilities tend to trigger false actions more often than users without disabilities. It is therefore helpful to plan the system in such a way that mistakes can be avoided in the initial phase.
{: .fs-6 .fw-300 }

Error prevention
{: .label .label-black }
Help users recognize, diagnose, and recover from errors
{: .label .label-black }

<img src="{{ '/assets/images/hero/support.png' | prepend: site.baseurl }}" alt="Title Picture support" title="Title Picture support"/>
{: .mt-6 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}


---

## What is the problem if the system does not provide support?
When users are disabled, they can often inadvertently trigger wrong actions. If this is the case, this should not be a problem for the user. The system should support the user and prevent errors from the beginning.

#### A system without support can be a problem for the following users:
{: .no_toc .mb-5 }

- Inexperienced or older users feel insecure
- People with physical impairments feel insecure if they accidentally click something wrong


---

## Error avoidance through restrictions
One possible way to avoid errors is to limit the user's options. By limiting the input possibilities, the error rate of a system is reduced. For users with limitations, it is more clear what is required of them.

<img src="{{ '/assets/images/support/support_restrictions.png' | prepend: site.baseurl }}" alt="In this example, the format of the input is already predefined and only the input of numbers is allowed."/>
In this example [ottonova](https://www.ottonova.de/expats "ottonova"){:target="_blank"} with a date, the format of the input is already predefined and only the input of numbers is allowed.
{: .fs-3 .mb-6 }

---

## Error avoidance through support
Errors can occur when entering information, not only for disabled users. This should not be a problem for the user. As a good example the live search should be considered. Suggestions are often made during the input. These suggestions also correct input errors. This avoids empty search results.

<img src="{{ '/assets/images/support/support_auto.png' | prepend: site.baseurl }}" alt="In this example, the format of the input is already predefined and only the input of numbers is allowed."/>
The automatic live search completion reduces the chance of errors during input. [google](https://www.google.com "google"){:target="_blank"}
{: .fs-3 .mb-6 }

---

## Error avoidance through repetition
Repeated requests for information force the user to check the information entered. In addition, by comparing the information, the system can detect errors and warn the user. A good example of this is setting a password. The user is forced to repeat this in order to avoid making errors. For actions with consequences, such as deleting a file, the system should always ask the user first whether this action is actually desired.

<img src="{{ '/assets/images/heuristics/control.png' | prepend: site.baseurl }}" alt="The image shows the deleting process of a file. The system asks the user if they really want to delete the file." title="The image shows the deleting process of a file. The system asks the user if they really want to delete the file."/>
The system asks the user if they really want to delete the file.
{: .fs-3 .mb-6 }

---

## Not all options are always available
Certain actions are dependent on other factors. For example, as a private user I need different input fields like an organization. Therefore, it makes sense not to display them for both users. It is better to separate both input variants. For example, with a radio button. This way, the user is not overwhelmed with too much information. Another example are inactive elements that only become active once everything has been entered. In this way, the user knows that he or she can now proceed to the next step. See <a href="/Accessibility-Designer-Guide/docs/Architecture/processes/">processes</a> for more information on processes and user guidance.

<div id="container1">
 <!-- The before image is first -->
 <img src="{{ '/assets/images/support/support_step1.png' | prepend: site.baseurl }}" alt="In this picture we see empty input fields, so the login button is still inactive.
"/>
 <!-- The after image is last -->
 <img src="{{ '/assets/images/support/support_step2.png' | prepend: site.baseurl }}" alt="In this picture we see filled in input fields, so the login button is active.
"/>
</div>
{: .mb-3 }
The system determines when it is possible to switch to the next step.
{: .fs-3 .mb-6 }

---

##### Links
{: .no_toc }

[W3C – Input Assistance](https://www.w3.org/WAI/WCAG21/Understanding/input-assistance "W3C – Input Assistance"){:target="_blank"} <br>
[W3C – Error Identification](https://www.w3.org/WAI/WCAG21/Understanding/error-identification "W3C – Error Identification"){:target="_blank"} <br>
[W3C – Error Prevention](https://www.w3.org/WAI/WCAG21/Understanding/error-prevention-legal-financial-data "W3C – Error Prevention"){:target="_blank"} <br>




