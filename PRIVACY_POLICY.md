# Privacy Policy for BergaHallen KTM

**Effective Date:** September 26, 2026

This Privacy Policy describes how **BergaHallen KTM** handles information when you use the Android application.

## 1. Decentralized and Self-Hosted Architecture

BergaHallen KTM is designed around a decentralized architecture.

BergaHallenKTM does not operate a central application server, central account system, analytics platform, or cloud database containing users' accounts, match histories, decklists, or game statistics.

The application can operate locally on the Android device and can optionally connect to a privately operated BergaHallen KTM server selected by the user.

## 2. Data Stored on Your Device

Depending on the features you use, the application may store information locally on your device, including:

* application settings and preferences;
* Local Mode players, decks, matches, history, and statistics;
* locally cached information from a connected server for offline functionality;
* server connection and trust information;
* QuickScan configuration and calibration information;
* card or deck information created or imported by the user.

This information remains under the control of the user and the Android device.

## 3. Self-Hosted Server Connections

If you choose to connect BergaHallen KTM to a self-hosted server, information required for the features you use may be transmitted directly between your Android device and that specific server.

This may include, for example:

* account and authentication information;
* player information;
* decks and decklists;
* match information and game statistics;
* synchronization data.

The server is operated by the user, another member of their play group, or another private server administrator.

BergaHallenKTM does not operate these server instances and does not have access to data stored on them.

## 4. Camera and QuickScan

BergaHallen KTM uses the device camera for features including:

* scanning a server pairing QR code; and
* scanning Magic: The Gathering cards using QuickScan.

Camera image frames used by these features are processed on the device and are not uploaded by BergaHallenKTM to a central service.

QuickScan recognition and OCR (Optical Character Recognition) are performed locally on the device using on-device machine-learning components.

Information derived from a scan, such as card information that the user chooses to save or add to a deck, may subsequently be stored locally or sent to the user's selected self-hosted server as part of normal app functionality.

## 5. Network and Nearby-Device Access

The application uses network access to communicate with self-hosted BergaHallen KTM servers selected by the user, as well as to fetch card reference data (see Section 6).

Where supported by Android, the application may also use nearby-device or local-network functionality to assist with discovering or connecting to a server.

BergaHallen KTM does not use these capabilities to collect device location for advertising or tracking.

## 6. Scryfall Integration and Attribution

To ensure accurate card recognition, QuickScan requires a local card reference database. The application connects directly to **Scryfall** (a third-party public card data provider) over the Internet to keep this database up to date.

Specifically, the application makes direct outbound requests to Scryfall to:
* perform an automatic, lightweight metadata check upon QuickScan startup (only when a validated Internet connection exists) to determine if newer public card reference data is available;
* download public card reference bulk data when the user explicitly requests or approves an update.

**Data Privacy regarding Scryfall:**
When the application connects to Scryfall, normal Internet metadata (such as your IP address and standard HTTP headers) is naturally visible to Scryfall and its hosting infrastructure. However, the application protects your privacy by ensuring that:
* Camera image frames and OCR processing remain strictly on-device.
* Your card scan history, saved decks, and collection data are **not** sent to Scryfall.
* Your BergaHallen KTM account details, server identity, and authentication data are **not** sent to Scryfall.

**Attribution:**
* QuickScan card data is derived from Scryfall bulk data.
* Scryfall is not affiliated with, nor endorsed by, BergaHallen KTM.
* Magic: The Gathering and card names are the property of Wizards of the Coast as applicable.

## 7. Third-Party Analytics, Advertising, and Tracking

BergaHallen KTM does not use:

* advertising networks;
* behavioral advertising;
* third-party analytics services;
* user-tracking services; or
* data brokers.

BergaHallenKTM does not sell user data.

## 8. Account Data

There is no central BergaHallenKTM account service.

Any account created for Server Mode belongs to the particular self-hosted server on which it was created.

The BergaHallenKTM developer does not have access to independently hosted user accounts.

Information about deleting accounts and application data is available at:

**https://bergahallenktm.github.io/ACCOUNT_DELETION.html**

## 9. Data Retention and Deletion

Local application data remains on the Android device until it is deleted by the user, removed through application functionality, cleared through Android's application storage settings, or removed when the application is uninstalled.

Data stored on a self-hosted server is retained and deleted according to the configuration and actions of that particular server and its administrator.

BergaHallenKTM does not retain copies of data stored on independently operated servers.

## 10. Children's Privacy

BergaHallenKTM does not knowingly collect personal information from children through any central service operated by the developer.

Because private BergaHallen KTM servers are independently operated, their administrators are responsible for access to and management of data stored on those server instances.

## 11. Changes to This Privacy Policy

This Privacy Policy may be updated when the application, its data-handling behavior, or applicable requirements change.

Updates will be published on this page together with an updated effective date where appropriate.

## 12. Contact

For questions about this Privacy Policy or the privacy design of BergaHallen KTM, contact:

**BergaHallenKTM**
**[bergahallenktm@gmail.com](mailto:bergahallenktm@gmail.com)**
