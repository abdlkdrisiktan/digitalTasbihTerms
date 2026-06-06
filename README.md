# Digital Tasbih – Privacy Policy Page

Static site hosted on Firebase Hosting.

---

## First-Time Setup

### 1. Install Firebase CLI
```bash
npm install -g firebase-tools
```

### 2. Log in to Firebase
```bash
firebase login
```
A browser window will open — sign in with your Google account.

### 3. Link the project (only needed once)
```bash
firebase use --add
```
Select your Firebase project from the list.

---

## Deploy

```bash
firebase deploy
```

After a few seconds you'll see a **Hosting URL** in the terminal output:
```
Hosting URL: https://your-project-id.web.app
```

---

## Quick Reference

| Command | What it does |
|---|---|
| `firebase login` | Authenticate with Google |
| `firebase use --add` | Link this folder to a Firebase project |
| `firebase deploy` | Deploy to Firebase Hosting |
| `firebase deploy --only hosting` | Deploy only the hosting (skip other services) |
| `firebase open hosting:site` | Open the live site in browser |
| `firebase logout` | Log out of Firebase CLI |

---

## Files

| File | Purpose |
|---|---|
| `index.html` | Privacy Policy page (TR / EN / DE / RU / AR) |
| `404.html` | Custom 404 error page |
| `firebase.json` | Firebase Hosting configuration |
