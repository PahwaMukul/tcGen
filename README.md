REG-001 | Verify that the user can register a passkey through the UAP flow and then sign in with it (end to end)
REG-003 | Verify that cancelling the device prompt during registration creates no passkey, and that the user can retry, register and sign in (end to end)
REG-022 | Verify that the passkey list shows the correct date, device label and last-used details after registration and after a passkey sign-in (end to end)
REG-028 | Verify that a passkey registered on this device is offered only on the device that holds it, and that another device without it cannot sign in with a passkey (end to end)
AUTH-029 | Verify that passkey sign-in is not possible before registration, and works right after the user registers a passkey (end to end)
AUTH-030 | Verify that after the passkey is deleted from the device, the user can still sign in with password and OTP, and the Register a passkey pop-up is not offered again (end to end)
AUTH-031 | Verify that a newly registered passkey still signs in after cookies and site data are cleared and after the browser is restarted (end to end)
AUTH-033 | Verify that a newly registered passkey cannot sign in while the Connect ID is locked, and signs in again after unlock without registering again (end to end)
POPUP-001 | Verify that the Register a passkey pop-up is displayed at every password and OTP sign-in until a passkey is created, and is never displayed again after a passkey is created
AUTH-009 | Verify that a Connect ID with no passkey can sign in with password and OTP, and the Register a passkey pop-up is displayed
REG-007 | Verify that refreshing the browser during registration leaves no partial or duplicate passkey, and the user can register again
REG-008 | Verify that closing the browser tab during registration creates no passkey, and the user can register again
REG-011 | Verify that pressing browser Back during registration cancels the flow cleanly without creating a passkey
REG-012 | Verify that opening another browser tab during registration creates only one passkey
REG-023 | Verify that clicking Register passkey twice quickly creates only one passkey
REG-009 | Verify that losing the network during registration shows a clear error, saves no passkey, and registration succeeds once the network is restored
AUTH-026 | Verify that losing the network right after approving the passkey prompt shows a clear error, and the user can sign in once the network is restored
AUTH-012 | Verify that the
