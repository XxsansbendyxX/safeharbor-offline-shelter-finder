# Install SafeHarbor on an iPhone

## Before you start
SafeHarbor is an installable web app (PWA), not a native App Store app. Host the folder at an HTTPS address. The offline app shell and saved directory work after the first online visit; the interactive map uses OpenStreetMap tiles and online address lookup, so the map itself requires internet access.

## Add it to the iPhone Home Screen
1. Open the hosted SafeHarbor URL in Safari on the iPhone.
2. Wait for the page to finish loading while online.
3. Tap Share, then choose Add to Home Screen. If shown, enable Open as Web App.
4. Tap Add and open SafeHarbor from the Home Screen icon.
5. Tap **Save directory to this device** while online.
6. Test search by ZIP code and neighborhood, accessibility details, and light/dark mode.
7. To test offline use, close SafeHarbor, enable Airplane Mode and turn Wi-Fi off, then reopen it. The saved directory should remain available; the online map will not.

## Features in this version
- Shelter map with address-based pins when online (sample locations only).
- Automatic warning when any listing is more than 30 days old.
- Detailed accessibility fields, including step-free access, restrooms, parking, service animals and communication support.
- Light, dark and device-default appearance settings.
- Directory version 1.1.0 and a notice when a saved directory version differs.
- Search by shelter name, street address, ZIP code or neighborhood.

## Important data note
The included shelter listings are fictional classroom sample data. Accessibility values marked "Not confirmed" must not be treated as a denial of access or as proof of access. The app does not connect to an official live shelter feed, and saving a listing does not verify availability. Before real-world use, replace sample entries with verified information from authorized local sources and confirm that update dates and accessibility details are maintained.

## Map and privacy
The map uses OpenStreetMap and Nominatim address search while online. Address queries are sent to that external service to place map pins. The map may fail offline, if the service is unavailable, or if an address cannot be located. Verify every pin before relying on it.

## This is not an App Store app
Publishing a native app through the App Store requires a separate Apple developer workflow, signing, review and maintenance.
