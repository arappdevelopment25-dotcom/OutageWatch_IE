# Privacy Policy for OutageWatch IE

**Last Updated: 18/12/2025**

## Introduction

OutageWatch IE ("we", "our", or "app") is committed to protecting your privacy. This Privacy Policy explains how we collect, use, and safeguard your information when you use our mobile application.

## Information We Collect

### Location Data
- **What we collect**: Your device's location coordinates (latitude and longitude)
- **How we use it**: To monitor power outages within your specified radius
- **Storage**: Stored locally on your device only
- **Sharing**: We do not share your location data with any third parties

### MRPN (Meter Point Reference Number)
- **What we collect**: Your 11-digit MRPN number (optional)
- **How we use it**: To check if your specific property is affected by power outages via ESB Networks' power check service
- **Storage**: Stored locally on your device only
- **Sharing**: We do not share your MRPN with any third parties. It is only used to pre-fill forms when you check your power status through the ESB Networks website
- **Optional**: You can skip entering your MRPN and enter it manually each time if preferred

### App Settings
- **What we collect**: 
  - Your alert radius preference (1-20 km)
  - Your monitoring location (latitude/longitude)
  - Notification frequency preference (10, 20, 30, or 60 minutes)
  - Notification type preferences (Fault, Planned Outage, Restored)
  - Premium purchase status (if applicable)
  - Onboarding completion status
- **How we use it**: To configure outage monitoring and notification preferences for your area
- **Storage**: Stored locally on your device using Android DataStore

## Third-Party Services

### ESB Networks API
- **Purpose**: We fetch power outage information from ESB Networks public API and check power status using your MRPN
- **Data shared**: When checking your power status, your MRPN is sent to ESB Networks' power check service (https://powercheck.esbnetworks.ie/)
- **Privacy**: ESB Networks' privacy policy applies to their service. We do not store or transmit your MRPN to any other services

### Nominatim (OpenStreetMap)
- **Purpose**: We use Nominatim for geocoding (converting addresses to coordinates)
- **Data shared**: Location queries only (no personal information)
- **Privacy**: Nominatim is a free, open-source service. See their privacy policy: https://operations.osmfoundation.org/policies/nominatim/
- **Attribution**: Map data © OpenStreetMap contributors (ODbL license)

### Google AdMob
- **Purpose**: We display advertisements to support app development
- **Data collected**: AdMob may collect device information, location (if permitted), and usage data for ad personalization
- **Privacy**: AdMob's privacy policy: https://policies.google.com/privacy
- **Opt-out**: Users can opt out of personalized ads in Android settings
- **GDPR**: AdMob handles GDPR consent requirements automatically

## Data Storage

- All data (location, MRPN, settings, outage information) is stored **locally on your device**
- We do not use cloud storage or external servers
- Data is stored using Android's built-in DataStore preferences
- You can delete all app data by uninstalling the app
- You can clear your MRPN at any time through the app's Settings screen

## Permissions

### Location Permission
- **Why needed**: To monitor power outages near your location
- **How used**: To calculate distance from outages and filter relevant notifications
- **Optional**: You can deny this permission, but the app will not function

### Notification Permission
- **Why needed**: To alert you about power outages
- **How used**: To send notifications when outages are detected or resolved
- **Required**: Android 13+ requires explicit permission

### Internet Permission
- **Why needed**: To fetch outage data from ESB Networks API
- **How used**: To retrieve current outage information

## Data Security

- We do not transmit any personal data to external servers
- All network requests are made directly to public APIs (ESB Networks, Nominatim)
- No user accounts or authentication required
- No tracking or analytics services used

## Children's Privacy

Our app does not knowingly collect information from children under 13. If you believe we have collected information from a child under 13, please contact us immediately.

## Changes to This Privacy Policy

We may update this Privacy Policy from time to time. We will notify you of any changes by posting the new Privacy Policy in the app and updating the "Last Updated" date.

## Your Rights

- **Access**: You can view and modify all stored settings (including MRPN) through the app's Settings screen
- **Deletion**: Uninstall the app to delete all stored data, or clear your MRPN through Settings
- **Control**: 
  - Configure notification frequency and types in the app Settings screen
  - Update or remove your MRPN at any time through the Settings screen
  - Disable notifications or location services at any time through Android settings
  - Adjust monitoring radius and location at any time

## Contact Us

If you have questions about this Privacy Policy, please contact us at:
- Email: arappdevelopment25@gmail.com

## Compliance

This app complies with:
- General Data Protection Regulation (GDPR) - applicable in Ireland and the European Union
- Google Play Store privacy requirements

---
