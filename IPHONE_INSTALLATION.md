# Install SafeHarbor on an iPhone

## Before you start
The app must be hosted at an HTTPS address. The service worker that makes the app shell available offline does not work from an ordinary `file://` link. A school-approved static host is suitable for a class prototype.

## Add it to the iPhone Home Screen
1. Open the hosted SafeHarbor URL in **Safari** on the iPhone.
2. While online, wait for the page to finish loading.
3. Tap the **Share** button (square with an upward arrow).
4. Choose **Add to Home Screen**. If shown, enable **Open as Web App**.
5. Tap **Add**. SafeHarbor should appear as an icon on the Home Screen.
6. Open SafeHarbor from that Home Screen icon while still online.
7. Tap **Download directory** and confirm the page says the information is saved on this device.
8. Close SafeHarbor, enable Airplane Mode, and make sure Wi-Fi is off.
9. Reopen SafeHarbor from its Home Screen icon and test the accessibility filter and shelter details.

## Important iPhone notes
- Use Safari for installation; other browsers may not offer the same Home Screen web-app installation flow.
- Keep using the same Home Screen app and browser profile where the directory was saved.
- Do not clear Safari website data or delete the Home Screen app before the test; doing so may remove saved information.
- Test offline behavior on the actual iPhone model and iOS version your team will demonstrate.
- The current app uses browser local storage for the sample directory. A production version should use stronger offline storage, signed/versioned data packages, and a carefully tested update mechanism.

## This is not an App Store app
This package creates an installable Home Screen web app (PWA), not a signed native iOS `.ipa`. Publishing a native app through the App Store requires an Apple developer workflow, signing, review, and ongoing maintenance.
