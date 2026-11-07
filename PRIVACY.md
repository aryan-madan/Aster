# Aster Browser Privacy Policy

**Last updated: November 8, 2026**

This policy describes the Aster browser app for macOS. It does not cover the Aster website, or websites, extensions, and services you choose to use in the browser.

## The short version

Aster does not run its own analytics or telemetry service, and the app code does not send your browsing history or search terms to Aster. Aster does store browser data on your Mac so the browser can work. Some app features also make connections to third-party services, as explained below. The websites you visit can collect information about you under their own policies.

## Data stored on your Mac

Aster and Apple's WebKit store browsing data locally, including cookies, website data, cached files, and other data needed by sites. Aster also stores browser information such as your saved tabs and workspaces, browsing history, downloads list, settings, and site permissions. These are stored in macOS app support, cache, and preferences storage. Website data is held in WebKit data stores; isolated workspaces use separate stores, and Incognito uses a non-persistent WebKit store.

If you choose to save passwords, Aster stores them in the macOS Keychain. Passwords are not sent to Aster. Imported passwords are also saved to the Keychain. Password import files are selected from your Mac; Aster does not upload them.

The app may cache website icons and download thumbnails on your Mac. Downloaded files are saved to the location you choose (or your macOS Downloads folder), and Aster keeps a local download list to show their status and location.

## Incognito

Incognito windows use a non-persistent WebKit website data store, so that store's website data is not kept as persistent browser data after the session ends. Incognito does not make you anonymous: websites, your network provider, and any network services you use may still see activity. Downloads and files you save remain on your Mac. Aster's source also uses its normal shared icon cache, so an icon fetched while browsing may be cached outside the Incognito website data store.

## Connections made by Aster

The browser itself does not upload your history, tabs, passwords, or browsing contents to an Aster account or Aster analytics endpoint. The app does make network requests for specific features:

- **Automatic app updates:** Sparkle checks the Aster update feed at `aster.aryan.am` automatically and can download and install updates. The update service will receive the ordinary connection information needed to deliver the feed and update, such as your IP address and request metadata. Aster does not receive your browsing history through this check.
- **Ad and privacy filter lists:** Aster downloads filter lists from uBlock Origin's public GitHub Pages, EasyList, Fanboy Annoyance, and PGL Yoyo services. Requests to those providers disclose ordinary connection information, including your IP address, to them. The downloaded lists are used to block matching web requests. Aster caches the compiled rules locally and refreshes them periodically.
- **Browser extensions:** If you install an extension, Aster may contact Google's Chrome Web Store update service to obtain that extension package. Extensions can also make network requests and access data according to their permissions and their own code. Review an extension's permissions and publisher before installing it.
- **Websites and search engines:** When you enter a web address or search, your request goes to the website or search provider selected by you or in your settings. Those providers receive your IP address and the request, and may use cookies or other technologies. Aster's built-in content blocker can block some known ad and tracking requests, but cannot guarantee that all tracking is blocked.
- **Site features:** A site may ask for access to features such as location, camera, microphone, notifications, or downloads. If you grant access, the site and relevant service providers may receive information needed for that feature. Site permissions and data are managed through WebKit and macOS.

These connections are separate from sending your browsing history to Aster: Aster does not operate the websites, filter-list providers, Apple WebKit services, or extension distribution services described above, and their handling of request data is governed by their own policies.

## Your choices and deleting data

You can clear browsing history through Aster's history controls. You can remove saved passwords in Aster's password settings; this removes the corresponding Keychain item. You can remove downloads from Aster's list, and delete downloaded files using Finder. You can change site permissions and browser settings in Aster. Clearing website data and cookies can sign you out of sites and remove site preferences.

Incognito is available for browsing without keeping persistent website data in its non-persistent store. It does not erase files you download or data collected by sites and network services.

## Apple's WebKit

Aster is built on Apple's WebKit. WebKit is the browser engine that loads and renders websites; it is not an Aster analytics service, and Aster does not configure a WebKit telemetry endpoint. However, WebKit is part of Apple's software, and macOS has separate, user-controlled diagnostics and analytics features that may send diagnostic or usage information to Apple when enabled. This is controlled by macOS, not by Aster. Apple documents these settings in its [Device Analytics & Privacy information](https://www.apple.com/legal/privacy/data/en/device-analytics/) and [macOS sharing settings](https://support.apple.com/guide/mac-help/share-analytics-information-mac/mh27990/mac). This does not establish that WebKit itself sends browsing history or telemetry to Apple. See [Apple's Privacy Policy](https://www.apple.com/legal/privacy/) for Apple's handling of data.

## Changes to this policy

If Aster's data practices change, this policy will be updated to describe the change and the date above will be revised.

## Contact

For privacy questions about Aster Browser, email [hi@aryan.am](mailto:hi@aryan.am).
