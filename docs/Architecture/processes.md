---
layout: default
title: Processes
parent: Architecture
nav_order: 9
---

# Processes
{: .no_toc }
{: .fs-9 }

When the user is in a process on the website, he follows instructions. He trusts that the steps he follows will lead him to the goal. Therefore, it is very important for us as designers to make this process as easy as possible for all user groups.
{: .fs-6 .fw-300 }

Visibility of system status
{: .label .label-black }
User control and freedom
{: .label .label-black }
Aesthetic and minimalist design
{: .label .label-black }
Help users recognize, diagnose, and recover from errors
{: .label .label-black }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is the problem with processes
If the user enters a process on a website or in an app, he trusts the system. There should never be a feeling that control has been relinquished or that errors may have consequences. 
{: .mb-8 }

#### A process can pose problems for certain user groups:
{: .no_toc .mb-5 }

- Inexperienced or older users feel insecure.
- People with screen readers find it hard to find their way around if processes are not implemented correctly.
- People with physical impairments feel insecure if they accidentally click something wrong in a process.

---

## Guide the user
The easiest way to make a process barrier-free is to guide the user. By guiding a process, especially disabled or inexperienced users feel more secure in their actions. But what are the possibilities to design a guided process?

### Show only what is important right now
We should only show what we ask of the user.  Therefore we design the process so that the focus is on this one current step.
{: .mb-8 }

#### the following example shows the problem
{: .no_toc .mb-5 }

<img src="{{ '/assets/images/processes/checkout_x.png' | prepend: site.baseurl }}" alt="In this example, all steps are listed below each other. Although it is pointed out that the previous step still needs to be filled in, such a process is not clear to all users."/>
In this example, all steps are listed below each other. Although it is pointed out that the previous step still needs to be filled in, such a process is not clear to all users.
{: .fs-3 .mb-6 }

### Show how easy it is
To give the user even more confidence, the past, current and upcoming steps can be listed in a reduced form. This makes it clear to the user where he is at the moment.

<img src="{{ '/assets/images/processes/checkout.png' | prepend: site.baseurl }}" alt="In this example we only show what is necessary and give the user the possibility to jump to the previous step if desired. For the user this screen is more clearly arranged."/>
In this example we only show what is necessary and give the user the possibility to jump to the previous step if desired. For the user this screen is more clearly arranged.
{: .fs-3 .mb-6 }

---

## Give the user control
People with disabilities, older users or people with visual impairments can quickly make false or unwanted interactions. Therefore, we should always give users the opportunity to correct their mistakes.

### Give the user confirmation
For a user to feel confirmed, it makes sense to show a summary of the steps to be performed. A classic example of this is a shopping cart that is listed again, or a list of all pictures that are sent.


### Edit selection afterwards
If we show the user a summary, this is ideally also editable. This allows users to correct any mistakes.

<img src="{{ '/assets/images/processes/checkout_edit.png' | prepend: site.baseurl }}" alt="In this process the individual items can be edited or removed again."/>
In this process the individual items can be edited or removed again.
{: .fs-3 .mb-6 }


### The process can be stopped at any time
Errors happen, and people with disabilities can quickly trigger unwanted actions. It is therefore recommended that processes can be stopped at any time. The system must be as tolerant of errors as possible.

---

## Give feedback
For all users it is confusing when the system completes an interaction or process without feedback. On the one hand you get the feeling that something has not worked. On the other hand, the user is not sure if the process took place at all. For users with disabilities who quickly make mistakes when using websites this is a accessibility problem. See also chapter [Application feedback](/Accessibility-Designer-Guide/docs/Architecture/application-feedback/) to get more detailed information about user feedback.

<img src="{{ '/assets/images/heuristics/visibility.png' | prepend: site.baseurl }}" alt="Picture of a sending process on a mobile phone, which shows the progress in the ui" title="Picture of a sending process on a mobile phone, which shows the progress in the ui"/>
In this example, the upload can be stopped at any time and the user can see exactly what is happening and how the process is progressing.
{: .fs-3 .mb-6 }



---

##### Links
{: .no_toc }

[Nielsen Norman Group – Visibility of System Status](https://www.nngroup.com/articles/visibility-system-status/ "NNgroup's Homepage"){:target="_blank"}





