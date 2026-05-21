# Privacy Policy — Vocabuddy

**Last updated: May 20, 2026**

This Privacy Policy describes how Vocabuddy ("the app", "we", "our") handles information when you use the Vocabuddy Android application (package ID: `com.driven.vocabuddy`).

---

## 1. Summary

Vocabuddy is an offline vocabulary-learning app. We do not collect, transmit, or store any personal information on external servers. All your data — saved words, quiz history, collections, and streaks — lives entirely on your device and never leaves it, except as described in Section 3 below.

---

## 2. Information Stored on Your Device

The app stores the following data locally in a SQLite database on your device:

| Data | Purpose |
|---|---|
| Words you save | Building your personal vocabulary list |
| Words you mark as mastered | Removing them from the active flashcard deck |
| Collections you create | Organising your saved words into groups |
| Search history (last 20 searches) | Showing recent searches for convenience |
| Quiz results per word | Weighting flashcards and quizzes by your accuracy |
| App open dates | Calculating your daily streak |
| Cached dictionary entries | Displaying previously looked-up words offline |

This data is stored only on your device. It is never uploaded to our servers or any third-party service. It is deleted if you uninstall the app or clear the app's data via your device settings.

---

## 3. Network Requests — Dictionary Lookups

When you search for a word that is not found in the app's built-in dictionary, the app sends the **search term** (the word itself) to one or both of the following free, public dictionary APIs in order to fetch a definition:

- **Free Dictionary API** — `https://api.dictionaryapi.dev`
- **Wikimedia REST API (Wiktionary)** — `https://en.wikipedia.org/api/rest_v1/`

These requests contain only the word you searched for — no personal information, no device identifiers, no account data, and no advertising IDs are sent. The response (definition, part of speech, example) is cached locally so the same word can be displayed offline in the future.

These are public APIs operated by their respective providers. Their own privacy policies govern any data they may log server-side (such as IP addresses in standard server logs). We have no control over and no access to those logs.

---

## 4. Information We Do Not Collect

We do not collect, process, or have access to:

- Your name, email address, or any other identifying information
- Device identifiers (IMEI, advertising ID, etc.)
- Location data
- Camera, microphone, or contacts
- Crash reports or analytics
- Any information about other apps on your device

---

## 5. Third-Party Services

The app does not integrate any advertising SDKs, analytics platforms (such as Google Analytics or Firebase), social login providers, or in-app purchase services. No third-party code with access to your data is included beyond the open-source Expo and React Native libraries used to build the app.

---

## 6. Children's Privacy

Vocabuddy does not knowingly collect personal information from anyone, including children under the age of 13. Because the app collects no personal information whatsoever, it is safe for use by all ages.

---

## 7. Data Security

All data is stored locally on your device using SQLite, protected by your device's own security model (encryption at rest if enabled on your device, app sandboxing enforced by Android). Because no data is transmitted to our servers, there is no server-side data at risk.

---

## 8. Your Rights

Since all your data is stored locally on your device, you have full control over it at all times:

- **Access and export:** All your data is in the app's local database on your device.
- **Deletion:** Uninstall the app or use **Android Settings → Apps → Vocabuddy → Clear Data** to permanently delete all stored data.

---

## 9. Changes to This Policy

If we update this policy (for example, when new features are added that affect data handling), we will update the "Last updated" date at the top and post the revised policy at the same URL. Continued use of the app after a change constitutes acceptance of the updated policy.

---

## 10. Contact

If you have any questions about this privacy policy, you can contact us at:

**Email:** vocabuddy.dev@gmail.com

---

*This policy applies to Vocabuddy version 1.0.0 and later, published on the Google Play Store under package ID `com.driven.vocabuddy`.*
