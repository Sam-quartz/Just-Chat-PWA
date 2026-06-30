
 **Just Chat** | Private Real-Time Chat App

A lightweight, zero-signup chat app that connects two people 
using a shared 6-digit room code. No accounts. No servers to manage. 
Just open, enter a code, and chat.


 Features
   **6-digit room code** — share with a friend to create a private chat room
   **Real-time messaging** — messages appear instantly on both sides
   **Offline resilient** — messages queue when signal drops and auto-send when back
   **Mobile-first** — works great on any phone browser
   **Private** — only people with your exact code can join your room
   **Clean dark UI** — easy on the eyes



Built With

- HTML / CSS / JavaScript (vanilla — no frameworks)
- [Firebase Realtime Database](https://firebase.google.com/) — free tier
- Single file — no install, no build tools needed



How to Use

 Option A — Run Locally
1. Download `index.html`
2. Open your own Firebase project and paste your config into the file
3. Double-click the file to open it in your browser
4. Share the file + a 6-digit code with your friend
5. Chat!

Option B — Use the Live Demo
 [Live Demo](https://YOUR-USERNAME.github.io/offchat)
*(Replace with your GitHub Pages link after enabling it)*


 Setup (Firebase Config)

1. Go to [Firebase Console](https://console.firebase.google.com)
2. Create a project → Add a Web App → copy your `firebaseConfig`
3. Enable **Realtime Database** in test mode
4. Open `index.html`, find the placeholder and paste your config:

```js
// 🔧 PASTE YOUR FIREBASE CONFIG HERE
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  databaseURL: "YOUR_DATABASE_URL",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
```
Note on Security

This is an MVP. For production use:
- Add Firebase Authentication
- Lock down database rules by authenticated user
- Add message encryption




Me
**Samuel A. Quartson**  
[GitHub](https://github.com/Sam-quartz)



License

MIT — free to use and modify
