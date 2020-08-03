---
title: "IT Assistance"
---

For all home access needs!

<!--more-->

## How to Download DoD Root Certificates

To access DoD websites from your personal computer, you will need to install the DoD Root certificates. **InstallRoot** is a program created by the Defense Information Systems Agency (DISA) to automate the installation. Here are instructions for installing the program and downloading the certificates:

**Note: This is for Windows systems only**

 1. Visit the [DoD Cyber Exchange](https://public.cyber.mil/pki-pke/pkipke-document-library/?_dl_facet_pkipke_type=tools) website (created by DISA) to download InstallRoot. 
 2. Scroll to the bottom of the page until you find "InstallRoot 5.X: NIPR Windows Installer". Most systems will be 64-bit.
 3. Click on the installer, save to your local computer, and run the program.
 4. Click "Next" all the way through and then click "Install".
 5. Once InstallRoot is installed, run the program. Click "Install Certificates" and then click "Ok".
 6. Restart Internet Explorer and try to open a DoD, CAC-enabled website.

{{<figure src="/assets/img/content/install-root-install-certificates.jpg"class="align center small">}}

## How to Read Encrypted Email in Outlook Webmail (OWA)

To access your military email from your personal computer, you will access it through OWA. OWA is accessible once the DoD Root Certificates are installed, but to read and send encrypted email you have to take the extra step of downloading S/MIME. S/MIME (or Secure/Multipurpose Internet Mail Extension) is a widely accepted standard for sending digitally signed or encrypted email. These instructions will show you how to use it in Internet Explorer.

**Note: This is for Windows systems only**

 1. Open Internet Explorer (make sure you use Internet Explorer and NOT Microsoft Edge).

{{<figure src="/assets/img/content/internet-explorer-icon.jpg"class="align center small">}}

 2. Log into OWA. There are different URLs for each reserve branch/region.
    * [Navy EAST](https://webmail.east.nmci.navy.mil)
    * [Navy WEST](https://webmail.west.nmci.navy.mil)
    * [Navy Europe](https://owa.eu.navy.mil/owa)
    * [Navy Middle East](https://owa.me.navy.mil/owa)
    * [Navy SOCOM](https://sofwebmail.socom.mil)
    * [DoD Enterprise Email](https://web.mail.mil) - Army and Air Force
    * [Marine Corps OWA](https://owa.usmc.mil)
    * [Coast Guard OWA](https://mail.uscg.mil/owa)

**If you are unable to reach these websites, you will need to download or update the DoD root certificates.**

 3. Accept the user agreement. Select your EMAIL certificate and enter your PIN.

 4. At the top-right of the page, click the gear icon and select "S/MIME settings".

{{<figure src="/assets/img/content/smime-settings.jpg"class="align center small">}} 

 5. Once you download and install SMIME, select the gear button at the top-right corner of Internet Explorer and go to Internet Options.

 6. Navigate to Security > Trusted Sites > Sites > Add.

 7. The URL for Outlook Webmail will be added to the list. Close Internet Explorer, then open again and go back to your email. Try to open an encrypted email (you will have to double-click the email to read it).

## 
