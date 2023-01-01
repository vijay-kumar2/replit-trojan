# replit-trojan

## Acknowledgements

- [Project X](https://github.com/XTLS/Xray-core)

## Overview

This project is used to deploy Trojan Websocket protocol on Replit free service with WS-0RTT support to reduce latency.

## Caution

 **Please do not abuse, account blocking is at your own risk. Network traffic has a soft cap of 100GB per month.**
 
 **Older Android devices certificate is not updated, if you can't connect, try to open skip certificate verification**

## Deployment
 
Go to replit.com to sign up for an account, then click the button below

<a href="https://repl.it/github.com/vijay-kumar2/replit-trojan">
  <img alt="Run on Repl.it" src="https://repl.it/badge/github/andbruibm/reader-replit" style="height: 40px; width: 190px;" />
</a>

Then click Import from Github.

### One-click auto-deploy

Click Run at the top of the page, wait a moment and the deployment will be finished, the right console window will automatically output the sharing link and QR code, you can use v2rayn/v2rayng client to scan the code.

Trojan password and Websocket path are randomly generated and stored in Repl database.

### Set up the deployment manually

Click Secrets on the left side and set the PASSWORD (Trojan protocol password) and WSPATH (Websocket path) variables respectively on the right tab.

! [image](https://user-images.githubusercontent.com/98247050/205805317-349f4814-5d1b-4fba-8d53-7de12a7f1810.png)

Then click Run at the top of the page and wait a few moments for the deployment to complete.

Example of manual client setup, with the server domain name in the address field of the Webview preview tab on the right: !

! [image](https://user-images.githubusercontent.com/98247050/205805711-75a6ddcf-20c6-4e2c-a90a-05dc979ade45.png)

To set up a custom domain name, click the pencil icon on the right side of the address bar of the Webview preview tab to enter the wizard.

