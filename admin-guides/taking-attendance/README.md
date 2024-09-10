---
description: >-
  Note: Make sure you have all of the prerequisites before proceeding with this
  guide.
---

# 🗽 Taking attendance

{% hint style="success" %}
In this section you will learn how to create and take attendance on Classmates+.

Please note that the attendance process is basically divided into two sections, the first section details how to create an attendance Id which would not initially be open for signing, then the second sections details how to activate the Id created so students could mark attendance on them.
{% endhint %}

## How to create attendance Id:

{% hint style="info" %}
**Note:** Only a mentor on duty would be able to create or activate attendance, if you're not the mentor on duty and you wish to create an attendance, kindly notify the mentor on duty to hand over to you, thereby granting you the administrative wright to create an attendance. for more details on handing over check the next section (Handing over to staff on duty).
{% endhint %}

* Navigate to [Classmates+ website](https://classmate-plus.vercel.app/), launch the App then click on the Program created, to access the Dashboard for that individual program.

<figure><img src="../../.gitbook/assets/created Programe.png" alt=""><figcaption></figcaption></figure>

* Click on the Attendance section of the sidebar, this should display an empty page for new users but should contain cards holding details of previous classes for old users. Next is to click on the create new attendance button at the top right hand side of the page.

<figure><img src="../../.gitbook/assets/Creating Attendance.png" alt=""><figcaption></figcaption></figure>

* A modal box containing a 3 input form should pop-up at this point, you're to fill the form in this order:

1. **NFT Image:** This is an image representation of the Nft that would be minted to each student that signs an attendance for that class.  &#x20;
2. **Day Id:** This is a numerical input designed to serve as a unique identifier for each class, please note that you should not repeat Id's as each Id is mapped to details of that particular class, Also note that this Day Id should be shared with the students when its time to take attendance.
3. **Topic:** This is supposed to hold the topic that was discussed on that particular day, it would be bound with the Nft and displayed to the students on their dashboard.

* Next is to click on the 'Upload Image' Button, this is an important step as it sends the uploaded image to IPFS then generates a CID that would be sent onchain to the smart Contract, NOTE: Please wait a couple of seconds until you receive a toast(notification) that the data has been submitted onchain before performing any further action.
* Finally, Click On the submit button.

<figure><img src="../../.gitbook/assets/attendance form.png" alt=""><figcaption></figcaption></figure>

* Submitting the form form the previous bullet point triggers our browser wallet to display a transaction requesting our signature. Click on the Confirm button to send your attendance creation request onchain to the smart contract.

<figure><img src="../../.gitbook/assets/confirm attendance form.png" alt=""><figcaption></figcaption></figure>

* After a couple of seconds the request is finalized on chain and if successful the Attendance details are submitted onchain and would be visible in the current attendance section.

<figure><img src="../../.gitbook/assets/attendance card.png" alt=""><figcaption></figcaption></figure>

