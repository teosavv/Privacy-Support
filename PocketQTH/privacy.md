# Privacy Policy for Pocket QTH

**Effective Date:** August 21, 2026  
**App:** Pocket QTH (`com.pocket.qth`)  
**Developer:** Teo Savvidis  

---

## 🔒 Commitment to Privacy

**Pocket QTH** is built with privacy as a core principle. We believe your location data and radio operational habits belong exclusively to you. 

- **No Third-Party Analytics:** We do not include any third-party tracking, analytics, or advertising SDKs.
- **No External Servers:** Pocket QTH does not operate external tracking servers or transmit your data to third parties.
- **Offline Operations:** All Maidenhead Grid Square calculations, GPS coordinate formatting, altitude determination, and antenna bearing math take place **100% locally on your iOS device**.

---

## 📍 Location Data Collection & Usage

Pocket QTH utilizes your device's Apple Core Location services solely to provide essential radio utility features:

1. **Real-Time Maidenhead Grid Square:** Your GPS coordinates are converted locally into a 6-character Maidenhead locator (e.g. `JO21vw`).
2. **Altitude & Bearing Math:** Used to compute elevation above mean sea level and exact antenna azimuths to target QTH locations.
3. **Live Activity & Lock Screen Widgets:** Used to update your current grid square banner on your Lock Screen and Dynamic Island while the app is active.

> **Note:** Location data is processed in real-time on your device and is never uploaded to any remote servers. You may grant or revoke Location permissions at any time via **iOS Settings ➔ Privacy & Security ➔ Location Services ➔ Pocket QTH**.

---

## ☁️ Data Storage & iCloud Synchronization

- **Local Storage:** Saved QTH bookmarks are stored securely on your device using Apple's native SwiftData framework.
- **iCloud Sync:** If iCloud is enabled on your device, your saved bookmarks sync across your personal Apple devices via Apple's secure CloudKit infrastructure. Your data remains encrypted in your private iCloud storage.

---

## 📧 Contact Information

If you have any questions or concerns regarding this Privacy Policy, please contact us:

- **Support:** [Pocket QTH Support Channel](support.md)
- **Developer:** Teo Savvidis
