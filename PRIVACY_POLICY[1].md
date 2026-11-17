# Privacy Policy — Hisab

**Effective date:** 17 November 2026  
**App:** Hisab — Personal Finance Manager  
**Developer:** Alindo Dhar  
**Contact:** Please use the [GitHub repository](https://github.com/alindodhar/Hisab-App) to contact the developer.

## 1. Overview

Hisab is designed as an offline-first personal finance manager. Its features include expense tracking, wallets, a due-and-receivable ledger, notes, budgets, reminders, optional payment-notification capture, and local export and backup tools.

This policy explains the intended data practices based on the app description and screenshots supplied with the project. The developer must verify that the published app's source code and included libraries follow these practices before treating this document as a final legal statement.

## 2. Information you enter

Depending on the features you use, you may enter or create information such as:

- Expense and income records.
- Wallet names, opening balances, and transaction amounts.
- Due-and-receivable records and related notes.
- Personal notes and checklist items.
- Budget limits, categories, and savings goals.
- Reminder preferences.

These records are intended to be stored locally on your device for the app's core functionality. Do not enter information you do not want stored on your device.

## 3. Notification access and payment alert capture

Hisab includes an optional Payment Alert Quick-Capture feature for supported bKash, Nagad, and bank payment notifications.

If you enable Android Notification Access for this feature:

- Android may allow Hisab to read notifications so it can identify supported payment alerts.
- Notification access is used to support the payment-capture feature.
- Payment notifications can contain sensitive financial or personal information. Enable this feature only if you understand and accept the access being requested.
- You can disable Notification Access or the feature through Android settings and/or the app, where available.

The exact notification fields read, extracted, retained, or discarded must be confirmed against the app's implementation before release. This policy does not claim that every notification is ignored after processing.

## 4. Reminders and notifications

If you enable reminders, Hisab may schedule local notifications and vibration alerts on your device. You can change reminder settings or revoke notification permission through Android settings.

## 5. Biometric authentication and PIN

Hisab offers an optional PIN and biometric lock interface.

Biometric authentication is expected to use Android's system authentication facilities. Android handles the biometric matching process; apps generally receive an authentication result rather than the user's fingerprint or face data. The developer should verify the exact implementation and how the PIN is stored before release.

Do not reuse a PIN that protects another important account.

## 6. Backups and exported files

Hisab provides options to export PDF statements, export CSV data, and create or restore backups.

- Exports and backups may contain sensitive financial information.
- You choose where to save or share exported files.
- Anyone who can access an exported file or backup may be able to view its contents.
- Store backups securely and delete copies you no longer need.
- Restoring a backup may replace or change information currently stored in the app. Review the in-app confirmation before restoring.

The developer should document whether backup files are encrypted and what data formats they contain. This policy does not promise that exported files are encrypted.

## 7. Data sharing and online services

The app is described as storing its records locally and supporting offline use. This policy is written on that basis.

Before publishing, the developer must inspect the complete app implementation and all third-party libraries to determine whether the app sends any information to a server or third party, including for analytics, crash reports, advertising, diagnostics, cloud backup, or update checks. If it does, this section must be revised to identify the data, recipients, purposes, and relevant choices.

The GitHub repository and release page are hosted by GitHub and are subject to [GitHub's Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-privacy-statement). Visiting those pages is separate from using the app locally.

## 8. Data retention and deletion

Locally stored records are intended to remain on your device until you delete them, clear the app's storage, or uninstall the app, subject to Android's storage behaviour and the app's implementation.

Uninstalling the app may permanently remove local records. Export or back up information you want to keep before uninstalling or clearing app data.

Files exported or backed up outside the app are not necessarily deleted when you uninstall Hisab. You must manage those files separately.

## 9. Children's privacy

Hisab is a general personal finance utility and is not intended to knowingly collect personal information from children through an online account or service. If the app's distribution or audience requires a specific age-related policy, the developer should add it here after reviewing applicable requirements.

## 10. Security

The app includes interfaces for local storage, backups, and optional app locking. No method of storage or transmission is completely secure. Keep your device updated, use a secure device lock, and protect any exported statements or backup files.

Do not treat the presence of a PIN or biometric option as a guarantee that every file or database on the device is encrypted.

## 11. Changes to this policy

This policy may be updated when app features or data practices change. The latest version will be published in the app's GitHub repository. Check the effective date at the top of this document.

## 12. Contact

For privacy questions or concerns, contact the developer through the [Hisab GitHub repository](https://github.com/alindodhar/Hisab-App).

---

**Important:** This document is a project-ready draft, not legal advice. The developer should verify every statement against the released APK and applicable privacy laws before publication.
