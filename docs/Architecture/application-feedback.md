---
layout: default
title: Application feedback
parent: Architecture
nav_order: 11
---

# Application feedback
{: .no_toc }
{: .fs-9 }

Through feedback we receive confirmation of our actions within a very short time. Digital systems have to communicate with their users in order to confirm their actions.
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

<img src="{{ '/assets/images/hero/feedback.png' | prepend: site.baseurl }}" alt="Title Picture Application feedback" title="Title Picture Application feedback"/>
{: .mt-6 }

---

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## What is the problem if the feedback is missing?
For all users it is confusing when the system completes an interaction or process without feedback. On the one hand you get the feeling that something has not worked. On the other hand, the user is not sure if the process took place at all. For users with disabilities who quickly make mistakes when using websites this is a accessibility problem.
{: .mb-5 }

#### This can be a problem for the following users:
{: .no_toc }

- Users who depend on screen readers and therefore need feedback from the system
- Inexperienced or older users feel insecure
- People with physical impairments feel insecure if they accidentally click something wrong

---

## Error message
Error messages are an important tool to give the user direct feedback on his action. But what do I have to consider so that error messages are useful and accessible for the user?

### Avoid technical terms
In order to make error messages barrier-free, technical terms should be avoided. This makes it easier for people with impairments and reading difficulties to recover from errors. See also chapter [Content and language](/Accessibility-Designer-Guide/docs/Architecture/content-and-language) to get more detailed information about accessible language. 

### Offer help
So that users can recover quickly from an error, not only an error message should appear. In addition, solutions should also be shown and, if necessary, quick-links and FAQs should be listed which could solve the problem. This shortens the search for a solution and people with disabilities have to search less on the site for solutions.

### Immediate error feedback
another way to communicate with the user is through direct and immediate feedback. Errors can be avoided already during the input of information. See also chapter [Support trough the system](/Accessibility-Designer-Guide/docs/Architecture/support-through-the-system) to get more detailed information about error prevention. 

#### Input
{: .no_toc }
Input fields are well suited for direct feedback. Through the immediate feedback and a correspondingly descriptive error message, the user immediately knows what was done wrong. This avoids mistakes during data entry and gives people with disabilities more confidence when using the system.

<img src="{{ '/assets/images/feedback/feedback_password.png' | prepend: site.baseurl }}" alt="In this picture the password was entered incorrectly. The password field is marked red and a label indicates that the password is wrong."/>
Through the direct feedback and the highlighting of the error, the user knows where the mistake has been made.
{: .fs-3 .mb-6 }

#### Processes
{: .no_toc }
If processes fail, they must also generate an immediate feedback. It should be noted that these are linked with suggested solutions or links to the FAQs.

<img src="{{ '/assets/images/feedback/feedback_process.png' | prepend: site.baseurl }}" alt="In this picture the allowed amount of data during upload was exceeded. The user is informed of this and a solution is suggested."/>
On [wetransfer](https://www.wetransfer.com "wetransfer.com"){:target="_blank"} the user is informed that he has exceeded the allowed amount of data. At the same time he will be shown how he could still send such a large amount of data.
{: .fs-3 .mb-6 }


---

## General error messages (404)
General error messages such as a "404 message" should not contain technical terms and should also contain further links. Useful for disabled users is a "back to home" button. This gives them an easy way back to the original page.

<img src="{{ '/assets/images/feedback/feedback_404.png' | prepend: site.baseurl }}" alt="On digitec.ch the error message is supplemented with a back to last page and back to home link. This is very useful for users with keyboard navigation or a screen reader. The customer service is linked directly to provide direct support for users."/>
On [digitec](https://www.digitec.ch "digitec.ch"){:target="_blank"} the error message is supplemented with a "back to last page" and "back to home" link. This is very useful for users with keyboard navigation or a screen reader. The customer service is linked directly to provide direct support for users.
{: .fs-3 .mb-6 }

---

## Success message
Along with the error messages, success messages are just as important to give a user confidence. Just like error messages they are important for users with disabilities to check their input.

#### Input
{: .no_toc }
Input fields are very well suited to confirm successful input. By confirming the e-mail format or the successful password retype, many errors in their creation can be avoided. 

<img src="{{ '/assets/images/feedback/validation.png' | prepend: site.baseurl }}" alt="The input fields are immediately checked for the correct format.In this picture this can be seen on a field with a checkmark."/>
On [github](https://www.github.com "github.com"){:target="_blank"} the input fields are immediately checked for the correct format.
{: .fs-3 .mb-6 }


#### Processes
{: .no_toc }
Processes can give successful immediate feedback. For example, sending a message can be indicated as successful, or transferring money can generate successful feedback. This gives inexperienced users or users with disabilities confidence in using the system.

<img src="{{ '/assets/images/feedback/message.png' | prepend: site.baseurl }}" alt="In this picture we see the 3 states a message can have in whatsapp. Successfully sent with a grey check mark, sent and received with 2 grey check marks and sent and read with two blue check marks. This way the user knows that the transmission of the message has worked."/>
On [whatsapp](https://https://faq.whatsapp.com/android/security-and-privacy/how-to-check-read-receipts "whatsapp faq's"){:target="_blank"} the sending of a message is immediately provided with a feedback. Successfully sent, sent and received and sent and read. This way the user knows that the message has been successfully sent.
{: .fs-3 .mb-6 }

---

## Confirmation message
In order to give users even more confidence in using the system, the system should ask the user before important actions if the action is really wanted. This is important for users with disabilities, as they can quickly trigger a wrong action.

<img src="{{ '/assets/images/heuristics/control.png' | prepend: site.baseurl }}" alt="The image shows the deleting process of a file. The system asks the user if they really want to delete the file." title="The image shows the deleting process of a file. The system asks the user if they really want to delete the file."/>
The system asks the user if they really want to delete the file.
{: .fs-3 .mb-6 }

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

<img src="{{ '/assets/images/heuristics/visibility.png' | prepend: site.baseurl }}" alt="Picture of a sending process on a mobile phone, which shows the progress in the ui" title="Picture of a sending process on a mobile phone, which shows the progress in the ui"/>
In this example the user is immediately shown that the sending is in progress. Also the progress of the process is shown to the user. Through this feedback the user knows that everything works.
{: .fs-3 .mb-6 }

### Pending
The process takes several days or weeks. For example, the processing of a document submitted online to the insurance company. Here it is important to display the current status in detail, so that the user can be sure that his or her request is being processed. Frequent updates ensure that inexperienced users or users with disabilities can handle the system with confidence.

<img src="{{ '/assets/images/feedback/pending.png' | prepend: site.baseurl }}" alt="In this picture we see a tracking for a package. The process is divided into several steps, which change depending on the status of the shipment until the shipment reaches the recipient."/>
[Feedex](https://www.fedex.com/en-us/home.html "feedex"){:target="_blank"} and many other delivery services allow the user to track the status of his delivery over a longer period of time.
{: .fs-3 .mb-6 }

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

<video width="100%" height="auto" controls>
    <source src="{{ '/assets/videos/snackbar.mp4' | prepend: site.baseurl }}">
</video>
[20min](https://www.20min.ch "20min"){:target="_blank"} communicates with the user via a snackbar and gives direct feedback to the user.
{: .fs-3 .mb-6 }

---

##### Links
{: .no_toc }

[W3C – Input Assistance](https://www.w3.org/WAI/WCAG21/Understanding/input-assistance "W3C – Input Assistance"){:target="_blank"} <br>
[W3C – Error Identification](https://www.w3.org/WAI/WCAG21/Understanding/error-identification "W3C – Error Identification"){:target="_blank"} <br>
[W3C – Error Prevention](https://www.w3.org/WAI/WCAG21/Understanding/error-prevention-legal-financial-data "W3C – Error Prevention"){:target="_blank"} <br>
[W3C – Status Messages](https://www.w3.org/WAI/WCAG21/Understanding/status-messages "W3C – Status Messages"){:target="_blank"} <br>

