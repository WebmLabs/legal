# AutoPDF Unlocker – Privacy Policy

**Policy version:** 1.0
**Effective date:** November 18, 2026
**Last updated:** November 18, 2026

## 1. Summary

AutoPDF Unlocker does not collect, transmit, or share personal data.

The app processes password-protected PDF documents entirely on your Android device. It does not require an account, does not use advertising or analytics services, and does not include tracking or crash-reporting services.

The app does not have internet access permission. Your PDFs and saved passwords remain on your device and are not uploaded to our servers.

This Privacy Policy applies to the AutoPDF Unlocker Android application:

- **Application name:** AutoPDF Unlocker
- **Application ID:** `app.webmlabs.autopdfunlocker`
- **Developer:** WebmLabs

## 2. Information Stored on Your Device

AutoPDF Unlocker stores limited information locally to provide its functionality.

This information is stored in the app's private storage, which is not ordinarily accessible to other applications.

| Information         | Description                                                                                                          | Protection                                                                                                                                        | How to Delete                                        |
| ------------------- | -------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------- |
| Saved PDF passwords | Passwords you choose to save for unlocking PDF documents                                                             | Encrypted at rest using AES-256-GCM, with the encryption key protected by Android Keystore                                                        | Delete individual passwords from **Saved Passwords** |
| Password labels     | PDF filenames associated with saved passwords and the number of times each password successfully unlocked a document | Stored in private app storage                                                                                                                     | Delete the associated saved password                 |
| Recent PDFs         | Copies of the last three PDFs you opened, including their filenames and opening dates                                | Stored in private app storage. Original password-protected documents remain encrypted; the app does not intentionally retain decrypted PDF copies | Use **Clear Recent PDFs** on the Open PDF screen     |
| Activity count      | The number of password-protected PDFs you have opened                                                                | Stored in private app storage                                                                                                                     | Clear app storage or uninstall the app               |
| Preferences         | Your selected theme and whether you have viewed the welcome screen                                                   | Stored in private app storage                                                                                                                     | Clear app storage or uninstall the app               |

When you open a PDF, the app accesses only the document you select through Android's file picker or share with the app through another application.

PDF processing takes place locally on your device. Saved passwords may be temporarily decrypted in memory when required to unlock a document.

## 3. Password Security and Encryption

Saved PDF passwords are encrypted using AES-256-GCM.

The encryption key is protected using Android Keystore, Android's secure key-management system. This helps protect saved passwords from being accessed directly from the app's stored data.

Passwords are not intentionally stored in plaintext in the app's persistent storage.

When a saved password is needed to unlock a PDF, it must be temporarily available in memory for processing.

The app does not transmit saved passwords to external servers.

## 4. Biometrics and Screen Lock

AutoPDF Unlocker may use Android biometric authentication to protect access to saved passwords.

The app does not receive or store your fingerprint, facial biometric data, or screen-lock PIN.

Authentication is handled by Android. The app receives only the authentication result indicating whether the verification succeeded or failed.

After one successful authentication, the app does not request authentication again until you close the app or leave it in the background for more than five minutes.

If your device does not have a configured screen lock or supported biometric authentication, certain password-viewing protections may be unavailable.

Biometric authentication does not mean that the app collects or stores biometric information.

## 5. Permissions

AutoPDF Unlocker requests only the permissions necessary for its functionality.

| Permission        | Purpose                                                                    |
| ----------------- | -------------------------------------------------------------------------- |
| `USE_BIOMETRIC`   | Allows the app to display Android's biometric authentication prompt        |
| `USE_FINGERPRINT` | Legacy permission for fingerprint authentication on older Android versions |

The app does not request permissions for:

- Internet access
- Contacts
- Camera
- Microphone
- Location
- Broad device storage access

You select the PDFs the app can access through Android's document picker or the **Open with** feature provided by other applications.

## 6. Data Sharing and Third-Party Services

AutoPDF Unlocker does not sell, rent, or share your personal information.

The app does not operate a backend server that receives your PDFs, saved passwords, or document contents.

The initial release does not integrate:

- Advertising networks
- Analytics services
- Tracking services
- Crash-reporting services
- Cloud-based PDF processing services

PDF documents and saved passwords are processed locally on your device.

## 7. Backups and Data Transfers

AutoPDF Unlocker opts out of Android cloud backup and device-to-device data transfer.

This means the app's private data, including saved passwords and locally stored PDF copies, is not intended to be included in Android automatic backups or transferred automatically to a new device.

Your saved passwords cannot be recovered by the developer if your device is lost, reset, or the app's data is deleted.

## 8. Data Retention and Deletion

Information stored by AutoPDF Unlocker remains on your device until you delete it.

You can remove information in the following ways:

- **Saved passwords:** Delete individual entries from the Saved Passwords screen.
- **Recent PDFs:** Use the Clear Recent PDFs option.
- **All app data:** Clear AutoPDF Unlocker's storage through Android Settings.
- **Complete removal:** Uninstall AutoPDF Unlocker.

Once app data is cleared or the application is uninstalled, the locally stored information and encryption keys may no longer be recoverable.

Because we do not receive or maintain copies of your information on our servers, we cannot remotely access, export, restore, or delete your locally stored data.

## 9. Children's Privacy

AutoPDF Unlocker is a general-purpose productivity application and is not specifically designed for children.

The app does not knowingly collect personal information from children or other users.

## 10. Changes to This Privacy Policy

We may update this Privacy Policy when the app's functionality, security practices, or data-handling procedures change.

Any updates will be published on this page with a revised **Last updated** date.

Material changes will also be communicated through the app's Google Play release notes when appropriate.

We encourage users to review this policy periodically.

## 11. Contact Information

If you have questions, concerns, or requests regarding this Privacy Policy, contact us:

**Developer:** WebmLabs
**Email:** webmstudio94\@gmail.com

---

© 2026 WebmLabs. All rights reserved.
