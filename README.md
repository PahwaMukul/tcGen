Hi,

Just wanted to highlight a limitation we’re facing with synced passkey testing on TD laptops.

In Chrome, personal Google account sign-in is restricted, so we can’t save passkeys through Google Password Manager. In Edge, although the TD account is already logged in, the organization has disabled the passkey option in Microsoft Password Manager.

We can successfully register and store the passkey on an external mobile device by scanning the QR code from the TD laptop.

However, we won’t be able to test using that same passkey from the mobile device on the TD laptop due to the restrictions on accessing personal cloud accounts.

So, we can test passkey registration on an external device, but we’ll need an alternative setup to validate the complete synced passkey authentication flow.