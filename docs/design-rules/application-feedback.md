---
layout: default
title: Application feedback
parent: Design rules
nav_order: 4
---

# Application feedback
{: .no_toc }
{: .fs-9 }

An action in the analog world, often has a reaction as a result. This gives us a very fast feedback if our action was correct or incorrect. This behaviour should be transferred to the digital world if possible.
{: .fs-6 .fw-300 }

Visibility of system status
{: .label .label-black }
Match between system and the real world
{: .label .label-black }
Error prevention
{: .label .label-black }
Help users recognize, diagnose, and recover from errors
{: .label .label-black }
Help and documentation
{: .label .label-black }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## The lack of response is no answer
For all users it is confusing when the system completes an interaction or process without feedback. On the one hand you get the feeling that something has not worked. On the other hand, the user is not sure if the process took place at all. For users with disabilities who quickly make mistakes when using websites this is a accessibility problem.
{: .mb-5 }

#### We take a closer look at the following immediate feedback options:
{: .no_toc }

- Error message
- Success message
- Confirmation message
- In progress message
- Status messages

---

## Error message
Error messages are an important tool to give the user direct feedback on his action. But what do I have to consider so that error messages are useful and accessible for the user?

### Avoid technical terms
In order to make error messages barrier-free, technical terms should be avoided. This makes it easier for people with impairments and reading difficulties to recover from errors. See also chapter [Content and language](/Accessibility-Designer-Guide/docs/Architecture/content-and-language) to get more detailed information about accessible language. 

### Offer help
So that users can recover quickly from an error, not only an error message should appear. In addition, solutions should also be shown and, if necessary, quick-links and FAQs should be listed which could solve the problem. This shortens the search for a solution and people with disabilities have to search less on the site for solutions.

### Immediate error feedback
another way to communicate with the user is through direct and immediate feedback.Errors can be avoided already during the input of information. See also chapter [Support trough the system](/Accessibility-Designer-Guide/docs/Architecture/support-through-the-system) to get more detailed information about error prevention. 

#### Input
{: .no_toc }
Input fields are well suited for direct feedback. Through the immediate feedback and a correspondingly descriptive error message, the user immediately knows what was done wrong. This avoids mistakes during data entry and gives people with disabilities more confidence when using the system.

![](//placehold.it/800x200)

#### Processes
{: .no_toc }
If processes fail, they must also generate an immediate feedback. It should be noted that these are linked with suggested solutions or links to the FAQs.

![](//placehold.it/800x200)

---

## General error messages (404)
General error messages such as a "404 message" should not contain technical terms and should also contain further links. Useful for disabled users is a "back to home" button. This gives them an easy way back to the original page.

![](//placehold.it/800x200)

---

## Success message
Along with the error messages, success messages are just as important to give a user confidence. Just like error messages they are important for users with disabilities to check their input.

#### Input
{: .no_toc }
Input fields are very well suited to confirm successful input. By confirming the e-mail format or the successful password retype, many errors in their creation can be avoided. 

![](//placehold.it/800x200)


#### Processes
{: .no_toc }
Processes can give successful immediate feedback. For example, sending a message can be indicated as successful, or transferring money can generate successful feedback. This gives inexperienced users or users with disabilities confidence in using the system.

![](//placehold.it/800x200)

---

## Confirmation message
In order to give users even more confidence in using the system, the system should ask the user before important actions if the action is really wanted. This is important for users with disabilities, as they can quickly trigger a wrong action.

![](//placehold.it/800x200)

---

## In progress message
Sometimes a process cannot be completed immediately. If this is the case it is important to mark it properly. This way, users can be sure that the process is running and the system has not crashed.
{: .mb-5 }

#### The following processes can be an example of such a case:
{: .no_toc }

- Insurance: documents are being processed by the agent.
- Sending files: the upload takes 10 minutes.
- Post: tracking of a parcel

We can separate longer lasting processes into 2 categories. 

### In progress
The process takes longer, but will be completed in the near future. As an example, this can be the upload of a large file. Here it is important to show the user the remaining duration and the current status. If such a process is executed in the background, the user is confused. It is also important to give the user the possibility to cancel such a process at any time. This helps users with disabilities, if they have triggered a wrong action.

![](//placehold.it/800x200)

### Pending
The process takes several days or weeks. For example, the processing of a document submitted online to the insurance company. Here it is important to display the current status in detail, so that the user can be sure that his or her request is being processed. Frequent updates ensure that inexperienced users or users with disabilities can handle the system with confidence.

![](//placehold.it/800x200)

---

## Status messages
System messages are an important feature for users with a screen reader to see what is happening on the website. 
{: .mb-5 }

#### Examples for system messages:
{: .no_toc }

- A user stores a link via a button in his clipboard. A short appearing snackbar shows the successful copying of the link.
- A user does not want to be disturbed and sets his status to "do not disturb". The status changes immediately.
- An item is added to the shopping cart and a short snackbar confirms this.

It is important that such system messages are displayed long enough to be read by a screen reader or a person with impaired vision. You should also not disturb or interrupt the current session.

![](//placehold.it/800x200)

---

##### Links
{: .no_toc }

[W3C – Input Assistance](https://www.w3.org/WAI/WCAG21/Understanding/input-assistance "W3C – Input Assistance"){:target="_blank"} <br>
[W3C – Error Identification](https://www.w3.org/WAI/WCAG21/Understanding/error-identification "W3C – Error Identification"){:target="_blank"} <br>
[W3C – Error Prevention](https://www.w3.org/WAI/WCAG21/Understanding/error-prevention-legal-financial-data "W3C – Error Prevention"){:target="_blank"} <br>
[W3C – Status Messages](https://www.w3.org/WAI/WCAG21/Understanding/status-messages "W3C – Status Messages"){:target="_blank"} <br>

