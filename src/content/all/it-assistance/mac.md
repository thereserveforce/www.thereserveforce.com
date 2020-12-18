---
title: "MacOS"
---

<!--more-->

## Obtain a Mac friendly CAC reader

In most cases your reserve center should issue you a CAC reader that is compatible with either Windows or MacOS. If you cannot obtain once from your reserve center, you can purchase one for less than $20. Here are a few you can try:

 - Rocketek RT-SCR10
 - Identiv SCR3500 Smartfold
 - ACR39U-N1 Pocketmate II

## Download your DoD Certificates

These certificates are required to access DoD CAC-enabled websites.

 1. Use the Shift + Command + U buttons to access your Utilities
 2. Find and double-click "Keychain Access"
 3. Select "Login" and "All Items" 
 4. Download the following five files. Once douwnloaded, double-click each one to install in your Keychain Access. When you double-click Mac Root Cert 3 and 4, you will need to tell your browser to always trust them.
 	- [Mac All Certs](https://militarycac.com/maccerts/MacAllCerts.p7b)
	- [Mac Root Cert 2](https://militarycac.com/maccerts/MacRootCert2.p7b)
	- [Mac Root Cert 3](https://militarycac.com/maccerts/MacRootCert3.p7b)
	- [Mac Root Cert 4](https://militarycac.com/maccerts/MacRootCert4.p7b)
	- [Mac Root Cert 5](https://militarycac.com/maccerts/RootCert5.cer)

## Firefox

Additional steps for Firefox. 

 1. Download the following certificates and double-click to unzip (there should be 39 files)
	- [All Certs](http://militarycac.com/maccerts/AllCerts.zip)
 2. With Firefox open, click "Firefox" on the top left and then click "Preferences"
 3. Click "Advanced" > "Certificates" > "View Certificates"
 4. Click "Authorities" and then click "Import"
 5. Import each file from the "AllCerts" folder. In the popup, check all 3 boxes and click "OK"
