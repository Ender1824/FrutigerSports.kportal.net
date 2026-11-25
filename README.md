# Frutiger Sports — website

The website for **Frutiger Sports**, a bright, bubbly sports game for iPhone where your phone is the controller. Swing it to play table tennis, golf, bowling and archery, on your own or against a friend nearby.

**Live site:** https://www.frutigersports.kportal.net

## Pages

| Page | URL | What it's for |
| --- | --- | --- |
| Home | [`/`](https://www.frutigersports.kportal.net/) | What the app is, the four sports, Play Nearby, and contact |
| Privacy Policy | [`/privacy/`](https://www.frutigersports.kportal.net/privacy/) | How the app handles information (App Store privacy policy URL) |
| Support | [`/support/`](https://www.frutigersports.kportal.net/support/) | Common questions and how to get help (App Store support URL) |

## About the app

- **Table Tennis:** your phone is the paddle. Tilt for forehand or backhand, swing as the ball arrives, and brush or chop for spin.
- **Golf:** swing your phone like a club, turn your wrist to hook or slice, and read the wind.
- **Bowling:** hold to grip, swing your arm and let go, turning your wrist to hook it.
- **Archery:** raise your phone like a bow, draw back, hold steady and allow for the wind.
- **Play Nearby:** two iPhones on the same Wi‑Fi can play head to head, with no accounts or sign‑in.

Frutiger Sports has no accounts, ads or tracking. Your profile and scores stay on your iPhone.

## How the site is built

Plain HTML and CSS: no frameworks, build step, cookies, analytics or third‑party requests.

```
index.html          Home
privacy/index.html  Privacy Policy
support/index.html  Support
styles.css          Shared styles
assets/             App icon, favicon, screenshots, social sharing card
CNAME               Custom domain for GitHub Pages
```

To preview locally, open `index.html` in a browser, or run a static server from this folder:

```bash
python3 -m http.server 8000
```

## Publishing on GitHub Pages

1. Push this folder's contents to the root of the repository.
2. In the repository, go to **Settings › Pages** and set the source to **Deploy from a branch**, using the `main` branch and the `/ (root)` folder.
3. The `CNAME` file sets the custom domain to `www.frutigersports.kportal.net`. At your DNS provider, add a `CNAME` record for `www.frutigersports` pointing to `<your-github-username>.github.io`.
4. Once the domain is verified, turn on **Enforce HTTPS** in **Settings › Pages**.

## Contact

Questions, bug reports or ideas: [universe@kportal.net](mailto:universe@kportal.net)

© 2026 Frutiger Sports
