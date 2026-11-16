# Privacy Policy

**Nasaan Kana?** · Last updated: November 16, 2026

Nasaan Kana? ("the app") is a free location sharing and chat app for families and friends, made by Levi Crown ("we", "us"). This policy explains what the app collects, why, who can see it, how long it is kept, and how you can delete it.

**The short version:** your location, history, places, messages, photos, videos, name and profile photo are encrypted on your phone before they are uploaded. Only the people in your circle hold the key to open them. We can't read them, and neither can Google, which hosts the encrypted data. We have no ads, no analytics and no tracking, and we never sell or share your data.

## 1. What the app collects and why

| Data | Why | Who can read it |
| :--- | :--- | :--- |
| **Email address and password** | To create your account and sign you in (Firebase Authentication by Google). We never see your password. A one-way hash of your email is also stored so the app can tell whether an account exists or was deleted. | Google (Firebase Authentication), for sign-in only |
| **Name and profile photo** | So your circle knows who you are. | Only your circle (end-to-end encrypted) |
| **Precise location, including in the background** | The main feature: your circle sees where you are on the map, even when the app is closed. You can pause it at any time with Ghost mode or turn sharing off. | Only your circle (end-to-end encrypted) |
| **Location history** | So your circle can see the places you visited and the trips you made in the last 24 hours. | Only your circle (end-to-end encrypted) |
| **Activity, speed, battery level, connection type and Wi-Fi network name** | Shown to your circle next to your location (for example "walking", "charging", "on Wi-Fi"). Activity comes from your phone's motion sensors. | Only your circle (end-to-end encrypted) |
| **Places** (such as Home or School) | To send arrival and leave alerts. | Only your circle (end-to-end encrypted) |
| **Messages, photos, videos, emoji and SOS alerts** | To chat with your circle. | Only your circle (end-to-end encrypted) |
| **Emergency number** (optional) | If you add one in Settings, the app calls it when you send an SOS. You can leave it empty. A personal number is checked first with a one-time code sent to it by SMS, so it is real and its owner agrees. | Stored only on your phone and wiped when you sign out. To send the code, the number is passed once to Google Firebase (Authentication), and the temporary record that creates is deleted right away |
| **Delivery and "seen" receipts, "typing…" status** | To show who got and read a message. These contain only times, never message content. | Your circle |
| **Technical data** (such as IP address and device information) | Needed by the services the app connects to in order to work (see section 3). We don't collect it ourselves. | The service that receives the request |

The app does **not** use advertising, analytics, crash reporting or tracking tools, and it doesn't access your contacts, call logs, SMS or files. The phone call permission is asked for only if you add an emergency number, and is used only to call that number when you send an SOS; if you don't allow it, your phone app opens with the number ready instead. Quick SOS can also use an Android accessibility service, only if you turn it on: it watches the volume-down button alone, so holding it sends an SOS while the app is closed. It doesn't read your screen or what you type, and it collects and sends nothing. Photos and videos are only read when you pick one to send.

## 2. How your data is protected

- **End-to-end encryption.** Each circle has its own secret key. Everything sensitive is encrypted on your phone with AES-256-GCM before upload, so the server only stores scrambled data.
- **Your keys are locked by your password.** Your circle keys are backed up to your account, sealed with a key derived from your password. On your phone they are protected by the Android Keystore. If you reset a forgotten password, the old keys can't be opened anymore, and you'll need a new invite to rejoin your circles.
- **Chat history on your phone** is stored in the app's private storage, encrypted with a key that only your account has. It is excluded from phone backups and device transfers.
- **Invite codes** work once and expire after 24 hours.
- **Server rules** only let members of a circle read that circle's data, and only you can change your own data.

## 3. Services the app connects to

| Service | What it receives | When |
| :--- | :--- | :--- |
| **Google Firebase** (Authentication and Cloud Firestore) | Your email for sign-in; the encrypted data above; and technical data needed to run the service | Always (this is where the app stores data) |
| **OpenFreeMap** and **Esri** (map images) | Requests for map images of the area on screen, and your IP address | When you view the map |
| **TomTom** (live traffic) | Requests for traffic images of the area on screen, and your IP address | Only while you have traffic turned on |
| **Open-Meteo** (weather) | An approximate location (rounded, not your exact position) | When you view someone's weather |
| **Your phone's address lookup** (Android Geocoder) | Coordinates, to show a street address. It is provided by your phone's system software. | When an address is shown |
| **GitHub** (APK version from GitHub only) | A request to check for a new app version | About twice a day, and when you check for updates |

Each service handles data under its own privacy policy. For Google Firebase, see [Firebase privacy and security](https://firebase.google.com/support/privacy).

We do not sell your data, and we do not share it with anyone else except where the law requires it. Because your content is end-to-end encrypted, we can't hand over what we can't read.

## 4. How long data is kept

| Data | Kept |
| :--- | :--- |
| Live location, location history, messages, photos, videos, receipts, invites | **24 hours** on the server, then deleted automatically |
| "Typing…" status and "someone is viewing" pings | 1 hour |
| Your chat history on your phone | Until you delete it, sign out, leave the circle or are removed from it. Only the newest 5,000 messages per circle are kept. Full photos and videos are not kept; small previews are. |
| Profile, places, circle membership and keys | Until **30 days after you last opened the app**, then deleted automatically |
| Your sign-in (email) in Firebase Authentication | Until your account is deleted |

## 5. Your choices and how to delete your data

- **Pause or stop sharing:** use Ghost mode, Battery saver, or turn sharing off in Settings. You can also deny or revoke the location permission in your phone's settings at any time.
- **Delete a message:** hold it and choose **Delete**. "Delete for everyone" works during the first 24 hours.
- **Leave a circle:** your membership and location in that circle are deleted, and so is that circle's chat history on your phone.
- **Sign out:** everything the app stored on your phone is wiped, including your chat history and keys.
- **Delete your account:**
  - **In the app:** open **Settings** and tap **Delete account** at the bottom. You confirm, type your password, and confirm once more. Your account and the data listed below are deleted right away, and you're signed out: your login, profile, keys, and everything you put in your circles (messages, photos, videos, location history, live location, receipts and your membership). Circles and saved places you share with others, and what other members posted, stay for them.
  - **Automatic:** an account that isn't opened for 30 days is deleted with its data.
  - **On request:** contact us (see below) from the email address on your account and ask for your account to be deleted. We'll delete your account and all data linked to it within 30 days and confirm when it's done.

## 6. Children

Nasaan Kana? is not directed to children under 13, and we don't knowingly collect personal information from them. If you believe a child under 13 has created an account, contact us and we'll delete it.

## 7. Changes to this policy

If this policy changes, we'll update the date at the top and publish the new version here. If a change significantly affects how your data is used, we'll also tell you in the app.

## 8. Contact

Questions, or want your data deleted? Contact Levi Crown:

- Telegram: [t.me/hachi0427](https://t.me/hachi0427)
- Facebook: [facebook.com/chris.benedict.00](https://web.facebook.com/chris.benedict.00)
- GitHub: [github.com/Levi-crown/NasaanKana](https://github.com/Levi-crown/NasaanKana)
