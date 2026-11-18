Hi,

Just wanted to highlight a limitation we’re facing with synced passkey testing on TD laptops.

In Chrome, we’re not allowed to sign in with personal Google accounts, so we can’t save passkeys through Google Password Manager. In Edge, although the TD account is already logged in, the organization has disabled the passkey option in Microsoft Password Manager.

We can still try registering through the TD laptop and scan the QR code using an external mobile device. The passkey should then be stored in the phone’s cloud account, provided the registration flow supports it.

However, we won’t be able to test using that synced passkey from the phone on the TD laptop because of these restrictions.

So, we can cover registration through an external device, but we’ll need an alternative setup to validate the complete synced passkey flow.