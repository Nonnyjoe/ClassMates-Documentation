---
description: >-
  Note: Make sure you have all of the prerequisites before proceeding with this
  guide.
---

# 🪧 Minting final certificate

{% hint style="info" %}
In this section you will learn how to mint final certificate to students on Classmates+
{% endhint %}

## How to Mint certificate of completion to users

* Design or have a ready made image for the certificate to be issued / minted to the students.
* Navigate to [Classmates+ website](https://classmate-plus.vercel.app/), launch the App then click on the Program you would love to interact with, to access the Dashboard for that individual program.

<figure><img src="../.gitbook/assets/created Programe.png" alt=""><figcaption></figcaption></figure>

* Click on the Certificate section on the sidebar, this should display an empty page because we've clearly not minted certificates to our students.
* Next, click on the issue certificate button on the top right side of the page.

<figure><img src="../.gitbook/assets/certificate issuance.png" alt=""><figcaption></figcaption></figure>

* A modal box containing a 3 input form should pop-up at this point, you're to fill the form in this order:

1. **Certificate Image:** This is an image representation of the certificate that would be minted to each student at the end of a .  &#x20;
2. **Program:** This is the name of the program that the certificate would be issued for.
3. **Year:** This is supposed to hold the year the program held.

* Click on the Upload file button on the form. this is very important as it sends out the certificate and data to IPFS then sends the generated CID to the organizations contract. Note: Please ensure to wait till the upload is completed onchain and you get a toast notification stating that&#x20;
* Finally click on the Submit button on the modal to submit, the certificate issuance request on chain.

<figure><img src="../.gitbook/assets/certificate form.png" alt=""><figcaption></figcaption></figure>

* Clicking on the submit button triggers our browser wallet to popup a transaction receipt which we are to confirm by clicking on the confirm button.
*

    <figure><img src="../.gitbook/assets/confirm certificate issuance.png" alt=""><figcaption></figcaption></figure>
* Depending on network congestion, after a couple of seconds the request is finalized on chain and if successful each registered student at that time is minted a certificate which is visible from the students dashboard.

<figure><img src="../.gitbook/assets/certification complete.png" alt=""><figcaption></figcaption></figure>

