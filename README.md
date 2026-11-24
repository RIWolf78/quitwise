# Quitwise MVP

A mobile-first, installable Progressive Web App prototype for smoking cessation.

## Included
- Four-week reduction plan (7, 5, 3, then 0 cigarettes/day)
- Cigarette logging with trigger categories
- Craving pause timer and coping suggestions
- Estimated savings and cigarettes avoided
- Local-device data storage and JSON export
- Basic offline caching\n- App icon assets for Home Screen installation

## Run locally
Serve this folder over localhost or HTTPS (service workers require a secure context):
`python3 -m http.server 8000`
Then open `http://localhost:8000`.

## Add to iPhone Home Screen
Deploy the folder to an HTTPS static host, open its URL in Safari, tap Share, then Add to Home Screen.

## Important MVP limitations
- Data stays in the browser on one device; no account, cloud sync, reminders, analytics, or payments.
- The four-week targets are a configurable self-help starting point, not individualized medical advice. Medication and withdrawal support should be discussed with a clinician or pharmacist.
- Savings/avoided counts are estimates based on the configured baseline and logged cigarettes.
- This PWA cannot itself be submitted to the App Store. App Store release requires an iOS app wrapper/native implementation, Apple Developer enrollment, build/signing, privacy disclosures, and App Review.
- The app is a prototype and needs usability, accessibility, privacy, and clinical-content review before public launch.
