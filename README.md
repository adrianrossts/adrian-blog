# Adrian Blog (Firebase Hosting)

## 1) Set Firebase project
Edit `.firebaserc` and replace `YOUR_FIREBASE_PROJECT_ID`.

## 2) Login
```bash
firebase login
```

## 3) Deploy
```bash
firebase deploy --only hosting
```

## Optional local preview
```bash
firebase emulators:start --only hosting
```
