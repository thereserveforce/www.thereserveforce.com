---
title: "Windows"
---


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

## How to perform the Cryptographic Logon (CLO) Enablement
**BLUF:** Sailors should perform the Cryptographic Logon (CLO) Enablement also known as the CLO Tool Alignment on their older CAC Cards. Sailors who have had new CAC cards created for brand new accounts since August are exempt completing this process. Their CAC cards are already CLO enabled.

**SITUATION:** After August 1st, ALL NMCI NIPR users must use the CAC-Logon (CLO) Realignment Tool to transition their NMCI account to a new 16 digit PIV authentication Certificate. This must be done before getting a new CAC card.

The Department of Defense is transitioning to one common authentication (logon) certificate on CACs called the “PIV Authentication” certificate. The PIV certificate is mandated as the new standard for all NMCI NIPR users. Users will no longer have to choose between ‘email’ and ‘identity’ certificates when logging into their workstations or any other NMCI NIPR services.


KEY POINTS:

 1. (First time) CACs issued after August 1st, 2020 will only have the “PIV certificate” available for authentication to all NMCI NIPR systems and services. SIPR and Alternative tokens are not affected by this change.

 2. Email certificates will only be used to sign and encrypt email.

 3. Users may realign their NMCI NIPR account to the PIV certificate at any time - but MUST transition their account to use the new PIV certificate PRIOR to issuance of new CACs after August 1, 2020.

 4. Failure to realign your account to the new certificate before being issued a new CAC may result in login failures to your NMCI NIPR workstation or any other CAC-enabled NMCI NIPR sites or applications

 5. Non-NMCI sites or applications may still explicitly specify usage of a different certificate to logon until the entire Department of Defense completes this transition.

 6. After realigning your account, users must wait at least 30 minutes for the changes to replicate throughout the network before attempting to use the PIV certificate for network logins.

**CLO Tool Alignment Direction:**

***This process must be done on a NMCI Computer.***  Please follow the directions below to the letter.

CLO Address: Https://cloenablementsite.nmci.navy.mil

Select your signature/DOD email cert and click ok to authenticate to the CLO Enablement Website.

 

REQUIRED ACTIONS:

1. Users must use Internet Explorer and browse to https://cloenablementsite.nmci.navy.mil

2. Select the ‘Signature’ certificate (Issuer: ‘DOD EMAIL CA-XX’) to log onto the CAC-Logon (CLO) Enablement Website.

3. Select ‘Click to Enter Website’ on the splash page.

4. Click ‘Continue’ on the next page.

5. Once logged into the CLO Enablement website with your Email certificate, users will see two tables.

     a. On the first table under the “Subject/Principal Name” column users will see “LAST.FIRST.MIDDLE” followed by their 10-digit DOD ID    number.

     b. In the adjacent column, users should see “DOD EMAIL CA-XX” under issuer.

     c. If you do not see ‘DOD EMAIL CA-XX’, choose “Select a Different Certificate” below and ensure you select your “Email” certificate.

6. In the table below, users will see their NMCI user name and NMCI domain:

     a. NADSUSEA – US East Users

     b. NADUSWE – US West Users

     c. PADS – INDOPACOM Users

7. Ensure “Realign my account to a different CLO-capable certificate” is selected.

8. Click “Continue”.

9. On the next page, click “Select New Logon Certificate”

10. The Windows certificate select window should appear: Select “More choices” and choose your Authentication certificate. Issuer should be “DOD ID CA-XX”.

11. The Certificate Realignment window displays the certificate currently aligned to your NMCI account and the new certificate you selected.

12. Click Continue to realign your account to the new certificate.

13. The Realignment Success window appears with a confirmation message that your account has been re-aligned.

14. Wait at least 30 minutes for the changes to replicate throughout the network before trying to use PIV certificate for network logins.

15. Remove your CAC from the reader and re-insert.

16. On the Windows logon screen, select “Other User” and then “Sign-in Options”. Select your 16-digit@mil (PIV) certificate).

17. Enter your PIN, and verify that you are able to log back into your workstation. The process is now complete.


## 
