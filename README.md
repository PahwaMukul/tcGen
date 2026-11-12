# tcGen
Testcases
Verify that a passkey registered in one browser can be used to sign in from another browser on the same device
Verify that the user can sign in on Device 2 using Device 2's own screen lock
Verify that the user can register a device-bound passkey using biometrics and then sign in successfully with it (end to end)
Verify that the user can register a passkey using device PIN / passcode / pattern and then sign in successfully with the same method (end to end)
Verify that when the OS passkey prompt is cancelled during registration, no passkey is created, and the user can retry, complete registration and sign in (end to end)
Verify that repeated user verification failures during registration do not create a passkey and a clear error message is shown
Verify that when the OS passkey prompt times out during registration, no passkey is created and the user can restart registration
Verify that registration on a device with no screen lock configured is blocked and the user is told to set up a screen lock
Verify that refreshing the browser during registration does not create a partial or duplicate passkey and the user can restart registration
Verify that closing the browser during registration does not create a passkey and the user can register again after reopening
Verify that a network disconnect during registration shows an appropriate error, no passkey is saved, and registration succeeds once the network is restored
Verify that pressing browser Back during registration cancels the flow cleanly without creating a passkey
Verify that opening another browser tab during registration does not interrupt the flow or create a duplicate passkey
Verify that registering a passkey on a second device is blocked with an appropriate message when a passkey already exists for the Connect ID (pilot rule)
Verify that the OS passkey prompt displays the correct app name and account name (Connect ID)
Verify that the passkey list, session details and last-used details are displayed correctly after registration and sign-in (end to end)
Verify that when the session expires before registration completes, no passkey is created and the user is prompted to sign in again
Verify that registration is handled correctly when the device clock is wrong, either completing successfully or failing with a clear error and no partial passkey
Verify that after deleting the existing passkey and registering a new one, the new passkey signs in and the old one no longer works (end to end)
Verify that when two devices attempt registration at the same time before any passkey exists, only one passkey is created and the other attempt is rejected

