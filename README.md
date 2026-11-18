Hi,

Just wanted to highlight a limitation we’re facing with synced passkey testing on TD laptops.

Since personal Google account sign-in is blocked on both Chrome and Edge, we can’t directly save or access synced passkeys through Google Password Manager on the laptop.

We can still initiate the registration on the TD laptop and scan the QR code using a mobile device. This way, the passkey can be saved to the phone’s cloud account (Google Password Manager or iCloud Keychain).

However, we won’t be able to test using that same synced passkey from the mobile device on the TD laptop due to the restrictions on personal account sign-in.

So, while we can test registration through an external device, validating the complete sync functionality will require an alternative setup or an approved test environment.