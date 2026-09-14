MEN'S FASHION HUB — FIREBASE STORE SETUP

Files:
- index.html = customer store
- admin.html = admin panel
- firebase-config.js = Firebase + WhatsApp settings
- firestore.rules = Firestore security rules

IMPORTANT:
1. Do NOT share your Firebase password.
2. Firebase web API keys are normally public; Firestore Security Rules are what protect the database.
3. Product image upload is not enabled in this package yet; admin currently uses a public image URL.

GITHUB:
Upload/replace these files in your GitHub Pages repository root:
index.html
admin.html
firebase-config.js

FIRESTORE RULES:
Firebase Console -> Firestore Database -> Rules
Replace the rules with the contents of firestore.rules and Publish.

ADMIN:
The admin login is restricted in the page to the configured admin email.
Use the same email/password account you created in Firebase Authentication.

WHATSAPP:
Orders are sent to the configured store WhatsApp number in firebase-config.js.
