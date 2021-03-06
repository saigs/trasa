---
id: tfa
title: Second Step Verification
sidebar_label: Second Step Verification (2FA)
---

import useBaseUrl from '@docusaurus/useBaseUrl';


Unless explicitly disabled by administrator, users require to perform second step verification for each security sensitive operation in TRASA dashboard or when accessing remote service. 

## Verification using TRASA mobile app

> verification process is same for both Android and IOS app


When you try to login using TRASA, you will be asked to choose a second step verification method.
<img  alt="2fa-prompt" src={('/img/docs/user-guides/2fa/2fa-prompt.png')} />

### Using TOTP (offline mode)
* Open the TRASA app on your phone and press the icon with your organization name under the "TRASA" section.

<img alt="enrol device" src={('/img/docs/tutorial/device-enroled.svg')} />

* Use the code from the TOTP generator page.

<img alt="totp" src={('/img/docs/user-guides/2fa/totp.svg')} />


### Using TRASA U2F (online mode)
* Enter blank TOTP code. You will get a notification on your TRASA app.
* Open the notification.

<img alt="u2f" src={('/img/docs/user-guides/2fa/u2f.svg')} />

* Press the "Authorise" button to login.
