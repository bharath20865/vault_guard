# Vault Guard

A responsive password strength checker and password generator. Password checks and generation happen in the browser; passwords are not sent to a backend or saved by this site.

## Publish with GitHub Pages
1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch **main** and folder **/(root)**, then click **Save**.
4. Wait for the Pages deployment to finish. The site URL will be shown in the Pages settings.

## Features
- Responsive layout for phones, tablets, and desktops
- Animated glass-style interface with reduced-motion support
- Password strength estimate and improvement checklist
- Random password generator using the browser crypto API
- Installable PWA manifest and service worker for offline caching

## Privacy note
The checker uses a local heuristic, not a breach database. Never enter a password you currently use on a sensitive account into a website you do not trust. This project does not transmit or store the entered password.
