# Match Checker

A single-page tool for checking a prospective marriage match against 22 areas: what you're looking for, what you bring, and how each match lines up.

- Open `index.html` in a browser, or visit the GitHub Pages site.
- Your picks and ratings are saved only in your own browser (localStorage). Nothing is sent anywhere.
- No build step: the whole app is `index.html`.

## Google sign-in (optional)

Sign-in uses Firebase. Until `firebase-config.js` has a config, the app saves to each device only.

1. Create a project at console.firebase.google.com and add a **Web app**. Copy its config into `firebase-config.js`.
2. **Authentication → Sign-in method:** enable **Google**.
3. **Authentication → Settings → Authorized domains:** add `mayankkjn.github.io` (and any custom domain).
4. **Firestore Database:** create a database, then paste `firestore.rules` into the **Rules** tab and publish.
