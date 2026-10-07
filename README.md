# sachinmamoru.dev

Personal portfolio. Plain static HTML, no build step: everything lives in `public/`.

## Preview locally

    python3 -m http.server 8000 -d public

## Deploy (Firebase Hosting, project `sachin-liyanage`)

    npx firebase-tools login
    npx firebase-tools deploy --only hosting

Previous releases stay in Firebase Console → Hosting → release history, so a deploy can be rolled back there.
